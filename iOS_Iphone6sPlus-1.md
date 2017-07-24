#### Test 12719871034799d6_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/12719871034799d6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B43021E2-0517-46E6-91A1-BE1A0C887DEF/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/B43021E2-0517-46E6-91A1-BE1A0C887DEF/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/12719871034799d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/12719871034799d6/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53837"
,(lldb)     command script import "/tmp/B43021E2-0517-46E6-91A1-BE1A0C887DEF/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
,2017-07-24 10:59:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 10:59:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 10:59:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 10:59:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 10:59:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 10:59:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 10:59:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AAED73F8-6B8E-4909-AB,31-E7655B09D711", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:AAED73F8-6B8E-4909-AB31-E7655B09D711
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:92D57CB5-389C-4D80-9BFE-,168A00163029
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:fo,undPeer:lostPeer:) peer:4FAEC5B8-A835-4A48-B413-952BCCC9E534
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5F657268-644B-4A00-83C0-C7DBA8A706C0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5F657268-644B-4A00-83C0-C7DBA8A706C0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F657268-644B-4A00-83C0-C7DBA8A706C0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F657268-644B-4A00-83C0-C7DBA8A706C0", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-24 10:59:23 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.592626869678497
,2017-07-24 10:59:23 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-07-24 10:59:23 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5F657268-644B-4A00-83C0-C7DBA8A706C0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5F657268-644B-4A00-83C0-C7DBA8A706C0", generation: 0)
,2017-07-24 10:59:24 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-24 10:59:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-24 10:59:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-24 10:59:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-24 10:59:26 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-24 10:59:26 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-24 10:59:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 10:59:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 10:59:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 10:59:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 10:59:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 10:59:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 10:59:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 10:59:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 10:59:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:00:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:00:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:00:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:00:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:00:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:00:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:00:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:00:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:00:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:00:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:00:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:00:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:52 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-07-24 11:01:52 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-24 11:01:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-24 11:02:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-24 11:02:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-24 11:02:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-24 11:02:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-24 11:02:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-24 11:02:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-24 11:02:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-24 11:02:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-24 11:02:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-24 11:02:19 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-24 11:02:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:02:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:02:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-24 11:02:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:02:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:02:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0D6C77A7-6FCC-4D01-8F22-52964B3E6445
[ThaliCore] Browser.startListening
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B7E1C62B-163F-496D-81A4-4A02323FB83C
[ThaliCore] Browser.startListening
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without e,rror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:02:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:02:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:02:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:02:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:02:25 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "76769C0F-ADFB-438D-943B-312E05DC747F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:76769C0F-ADFB-438D-943B-312E05DC747F
2017-07-24 1,1:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:02:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising(,)
[ThaliCore] Advertiser.stopAdvertising() peerID:76769C0F-ADFB-438D-943B-312E05DC747F
2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:26, - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "34983E85-166A-47F8-BC90-82B4DDF293CD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:34983E85-166A-47F8-BC90-82B4DDF293CD
,2017-07-24 11:02:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "34983E85-166A-47F8-BC90-82B4DDF293CD", generation: 1)
[,ThaliCore] Advertiser.startAdvertising with peerID:34983E85-166A-47F8-BC90-82B4DDF293CD
2017-07-24 11:02:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:27, ,- INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:02:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:0,2:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:34983E85-166A-47F8-BC90-82B4DDF293CD
[ThaliCore] Advertiser.s,topAdvertising() peerID:34983E85-166A-47F8-BC90-82B4DDF293CD
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:02:28 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:28 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:02:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "489BD2DA-ED40-4C42-A931-8C514A214BF5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:489BD2DA-ED40-4C42-A931-8C514A214BF5
2017-07-24 1,1:02:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:02:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 11:02:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A7987A9E-1588-4581-BC75-402CFEA9C60C
[ThaliCore] Browser.startListening
2017-07-24 11:02:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-24 11:02:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A8BB093A-4D70-46E4-9D84-4E14AF3D9C9B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8BB093A-4D70-46E4-9D84-4E14AF3D9C9B", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9699B0E1-44B9-482F-A4AC-FD3E9344992A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9699B0E1-44B9-482F-A4AC-FD3E9344992A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:489BD2DA-ED40-4C42-A931-8C514A214BF5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "489BD2DA-ED40-4C42-A931-8C514A214BF5", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,11:02:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 11:02:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:489BD2DA-ED40-4C42-A931-8,C514A214BF5
2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:02:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:02:30 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:01BFBF0D-498C-4989-932F-2BFF5B82FD2A
2017-07-24 1,1:02:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6FB004D3-5820-42BE-8A1C-23C107D2FEA3
[Thal,i,Core] Browser.startListening
2017-07-24 11:02:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:02:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:35 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:44385B8E-CCD5-46CA-A26D-618FC8342DC1
,[ThaliCore] Advertiser: session connected Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
,[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:44385B8E-CCD5-46CA-A26D-618FC8342DC1 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9437DC0E-0407-4771-AF4C-DA9C3D8A287D
[ThaliCore] Advertiser: session connected Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9437DC0E-0407-4771-AF4C-DA9C3D8A287D state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
,2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD1166F3-65E0-4A9D-9015-16F0811DA565","generation":0}'
,2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FD1166F3-65E0-4A9D-9015-16F0811DA565 (syncValue: GGU5uloNbvgNkCvgKsmmQxBjp9iBIvwZ)'
2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:381B7A74-7122-4015-A89E-4B737500991B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "381B7A74-7122-4015-A89E-4B737500991B", generation: 0)
,2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"381B7A74-7122-4015-A89E-4B737500991B","generation":0}'
,2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9437DC0E-0407-4771-AF4C-DA9C3D8A287D
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:44385B8E-CCD5-46CA-A26D-618FC8342DC1
[ThaliCore] Session.session(_:peer:didChange:) peer:9437DC0E-0407-4771-AF4C-DA9C3D8A287D state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:44385B8E-CCD5-46CA-A26D-618FC8342DC1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59567
2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GGU5uloNbvgNkCvgKsmmQxBjp9iBIvwZ","error":null,"portN,umber":59567}'
2017-07-24 11:02:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GGU5uloNbvgNkCvgKsmmQxBjp9iBIvwZ', error: 'null', listeningPort: '59567''
,2017-07-24 11:02:39 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,2017-07-24 11:02:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:01BFBF0D-498C-4989-932F-2BFF5B82FD2A
2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11,:,02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:FD1166F3-65E0-4A9D-9015-16F0811DA565
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59567
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9437DC0E-0407-4771-AF4C-DA9C3D8A287D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:9437DC0E-0407-4771-AF4C-DA9C3D8A287D
[ThaliCore] Advert,iserRelay.deinit
,# setup
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GGU5uloNbvgNkCvgKsmmQxBjp9iBIvwZ","error":"Session disconnected","portNumber":null}'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FD1166F3-65E0-4A9D-9015-16F0811DA565","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FD1166F3-65E0-4A9D-9015-16F0811DA565","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:44385B8E-CCD5-46CA-A26D-618FC8342DC1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,[ThaliCore] Session.deinit peer:9437DC0E-0407-4771-AF4C-DA9C3D8A287D
[ThaliCore] Session.deinit peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E2A40D56-96CA-4D8D-8F53-D4CC01876154
2017-07-24 1,1:02:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A448B215-5A97-4EB5-B3F8-D3AC2616C312
[Thal,i,Core] Browser.startListening
2017-07-24 11:02:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:02:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:44 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
,2017-07-24 11:02:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD1166F3-65E0-4A9D-9015-16F0811DA565","generation":0}'
,2017-07-24 11:02:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FD1166F3-65E0-4A9D-9015-16F0811DA565 (syncValue: BV4YSKiNMaTGc494XpUWzxHkXe9guAHN)'
,2017-07-24 11:02:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:381B7A74-7122-4015-A89E-4B737500991B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "381B7A74-7122-4015-A89E-4B737500991B", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
,2017-07-24 11:02:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"381B7A74-7122-4015-A89E-4B737500991B","generation":0}'
2017-07-24 11:02:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:02:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:02:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6","generation":0}'
,2017-07-24 11:02:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:02:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:02:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
2017-07-24 11:02:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5ACAF211-0772-4AB0-B392-E6D7695E2A89","generation":0}'
2017-07-24 11:02:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:02:46 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 11:02:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:02:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,D1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:381B7A74-7122-4015-A89E-4B737500991B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "381B7A74-7122-4015-A89E-4B737500991B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,D1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:FD1166F3,-65E0-4A9D-9015-16F0811DA565 error: max retries exceeded
2017-07-24 11:02:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BV4YSKiNMaTGc494XpUWzxHkXe9guAHN","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:02:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BV4YSKiNMaTGc494XpUWzxHkXe9guAHN', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:02:55 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"FD1166F3-65E0-4A9D-9015-16F0811DA565","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:02:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-24 11:02:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FD1166F3-65E0-4A9D-9015-16F0811DA565","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 11:02:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:02:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:02:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6 (syncValue: yIBGeHv,LZLxXlBpdAV5BnJ5iMVxchIol)'
2017-07-24 11:02:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BD9F2C7A-F67B,-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:02:55 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-24 11:02:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:19E8B9BE-AE9D-4FFF-923D-133A5A914DE0
[ThaliCore] Advertiser: session connected Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:19E8B9BE-AE9D-4FFF-923D-133A5A914DE0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:19E8B9BE-AE9D-4FFF-923D-133A5A914DE0
,[ThaliCore] Session.session(_:peer:didChange:) peer:19E8B9BE-AE9D-4FFF-923D-133A5A914DE0 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:19E8B9BE-AE9D-4FFF-923D-133A5A914DE0
[ThaliCore] Session.startOutputStream(with:) peer:19E8B9BE-AE9D-4FFF-923D-133A5A914DE0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
,2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] Session.session(_:peer:didChange:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59576
,2017-07-24 11:02:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yIBGeHvLZLxXlBpdAV5BnJ5iMVxchIol","error":null,"portNumber":59576}'
2017-07-24 11:02:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yIBGeHvLZLxXlBpdAV5BnJ5iMVxchIol', error: 'null', listeningPort: '59576''
,Connecting to the localhost:59576
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
,Connected to the localhost:59576
,2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 []
,ok 88 got the same data back
,# teardown
,2017-07-24 11:02:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:02:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E2A40D56-96CA-,4D8D-8F53-D4CC01876154
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59576
[ThaliCore] Session.disconnect() p,eer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:19E8B9BE-AE9D-4FFF-923D-133A5A914DE0 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:19E8B9BE-AE9D-4FFF-923D-133A5A914DE0
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:19E8B9BE-AE9D-4FFF-923D-133A5A914DE0
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3
2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E5908147-7A14-434D-B742-7872530D4239
[ThaliCore] Browser.startListening
2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-24 11:02:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
2017-07-24 11:03:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6","generation":0}'
2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6, (syncValue: 1k04mhUP2nvfesrGDBZO6REI6bDApzRW)'
2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC,2A0B6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"5ACAF211-0772-4AB0-B392-E6D7695E2A89","generation":0}'
2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B7A64547-3C92-4AEA-B913-F34E280DDD7C","generation":0}'
2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:01 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8DB5C8CF-9F6C-4FCE-AE67-31A370211A57","generatio,n,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
":0}'
2017-07-24 11:03:01 - ,DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:01 - DEBUG thaliMo,bileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,D9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,D9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA
[ThaliCore] Advertiser: session connected Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,D9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA
,[ThaliCore] Session.session(_:peer:didChange:) peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA
[ThaliCore] Session.startOutputStream(with:) peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA
[ThaliCore] Session.startOutputStream(with:) peer:7FED5B98-CE04-4E64-9EB3-69D28316,59CA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA
[ThaliCore] Session.st,artOutputStream(with:) peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 11:03:08 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-24 11:03:08 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-24 11:03:08 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
2017-07-24 11:03:08 - DEBUG testThaliMobileNative: 'Server received (2504 bytes):'
2017-07-24 11:03:08 - DEBUG testThaliMobileNative: 'Server received all data: NKlxD88lZf,ffHVCemA7I3dVbtaBWjMrSEfMhWPiEcXAXYpNad3ec4KFrzomYno8VLunjcZCvgmN9LC76ko0DaNtB7Pj3AtC1WNY82sGDCTXb9zLzJNiIDCxptMCgiQDR3OaMD9eVHAntYmFsbLTFnpNBW8Z3Rfcn5xANVKSyKuvSGbyaxSk0wMAtUobu27GMP2o5snIUgI0YlRZ1rBMkJ9IbfrwwQ794SZ4YALjLqbBvavOX0ATuvANyJRJlTM1hE6azbHkxZx,UgNSoiDXq3ZJO374KSnZvcpzQawLs5PtjUpCMDATQXvV5kHzxnOjLKjlmuZRt6hGkjKBMe1SBTwiAzwXmkOZl72lLCRGe8N9KsteCp5bdw0qgTCE5yEKFHseCdhTu7NdpBCvF44ZJUU4tUZoFjKHJ4KywSj3lxYeDQAD09V5iLAGjh9BUwYcYnnCn6IBHrNkl31aur9wzpDmvudgQG8xUwZCUp5ja7FAuYjtoXnLqH1xh8S6UEog9JdH4NE7axLg,sX349qPUb3Bq2IeRz3aS9IxhDdXr0NFPNIgnO9HUO8CWZuJFx0TDi315QEesAGPNf5teXNmcT6IkvClYRkxp6bIKxaB60RLyK5781yKLjDTh7b3taILb0ogn5jKzaBflcf7ItuiZfKYdPbZ6TjAV5uwMDXl6KZQxh4n42ozU9FtKUvCZZckc5aPpqRaQuL7ilfeDlLUcPun9MXw3uwcgDt6T6EcviRGAGo5zkcvP7Kd5w9Dgkfyvc4J0aDvmwxZ,j,WBwOeyAaeLotj86LuhP09z6BaWWmspfK0duQ2EQmshc6LzAYqn18jdNWmDeh39iDlnrBmP6qR9aaFxMCHug7DPbmvvmvZA2evXwyNP8TcDRJSO9pNTlrUletxFOUUvWU9ZZsL0RxNovs3nJddJroPNXd8CoxHOjlIOUWnJAedCwxxrITsCKGHfEPZP9pBz6bnMWXCjAhxqCw4fE633AJLsrgwPxoG9XoR0Ti2X49cCubOcA772C0uz38qNm56EHo,Hb7lGzePd76OQH9MKfTDf5bQhCYi8zHUXoig5FNCdjV4V0Mps12s3MF9d0U1YFiHK4CTlGy2nTqUIoUTKIb9z1SG020KBHkfF0ghh9aOkGTjOzkErlyZz8AfOZMfTSO72LoI9t5RMBGxHigaPbJTtPF0QVsmOHYnu2Bmm5uyBjUDak6Pw3xXiE7mYk4LXv18U703wKyfH3QeMD2ru7URNivJzd0c53kixckb1pBTzUGCvffebnBGeHyueemaOMTs,riHvTopit5QPWxDzs22A48SluAYwa0YJUZI9M12tgs5NEPEtSAQmkScj82U5t0CWco2ZoZ8Q1FDP3dJKA2Vm6MWkxt6C6wY465oEg9DD1pVSFegjU57ljXBpQXgeCCNrFzhNIohQEYwnR5OkXpruZhsFypNPwW719PDqV9oFc0GBFn7FvndMmznnx7UcpzZRCUHEZM3gpKDu1rE5RRY7qmkmZk4hVMz8FPXanp9xGQdmd0snKqGQCw6Kj1rQj2hJ,KlpT07nuUojqbLizuq99gxAK6nqYYTXTl9k3a2eLeaoDhykkY9S60G9fJFgnelnoXOZKXY7pLEPmKYf1AZayOgd0ttPVzp2Sz1WIwR8c1wsnHxqy0L41EtmUzBG5ys6ekR34MCuZwdICgBbuvqOB0Ud4Hb63HopZOA8TXLVYi4BNGK03WqrLtahdKmlnM0YRjW1CpBl81VX4KdpfzmWmUkn42aLZYK9kTQXb3i6AzEhpnWnCl7vsn9ElGbeKIhj,l,Chw1PvEGaxiyMb4tzSQZ5v55GgEgbAsTrLeC3rsMetRtwHkDB5TNXSmPDs8SY81cm69bSQxelH8sIgtWQq1ahHeeWALNuUo0WeK07B9qwNl1xb30bE5I6cQ8MLZADMrjxhYzjqZ5fXBmt4jEl569gXwN3gPZgM5Y36sZg9sd55YtfTFYXYnBnhAxbHrR5tdStpaRGgdHWwS3EnuMG0VM4aUtrjRmsLQoxkhqqg3WpMTWqMyGFCjNyycUSMREl2ZV,9D1PON0ve1uSp4tkvhWxLLxKsoJn6Amj0GWyyQbCKdNYIwBzZS34XPmYHoimUcdDGbf1J2ycyIAYWFdFE0dnQumCfDjrh3WanDA3FhOGh73giEtmdcpSHhMjDPvDdqpWYbiJydQqeQvHTNvZuouiOW1KAOXp65IqydCKvkQ2QO4M1z0mQ2kHlXJCABzjeI8jj7k4VZ3Dg6vXQkgBt5zCDMkUjavzawWYOQ63BdQM6CjjwZxTK8ZuthRHcAVnXI2l,rElRGQXvi3I6SfK3YMcE3RRdUQb5qhAzwhCRMzBgHIMNmGR8Bw7MraWX6KLvu6Ie8Hef7pDzFJiK991B9xOGuf9xyWbijA629M9EXFIzQwPdd48lKylz5eVI203Oqkz1aV80GdaJn6GdGK00lOsgMqYASxkKL0656zgBUa8fQTPsUVhSnjGXgOFpxN81U5Cey20gmxwrFFFjX31AUNUhLfw1mQN47nx6J1dTO3K0JtrRFgnhsEP23aflNYRRSWVV,vwzX4SnSHF71ZoPeyP9t93bZBwv5OJem6QC1mppxjOsHoKUz25axGpy8AYk4rLjx5OoACQPpIv4cqPPGiWs5q46YFXNUkFEvouWnIJqa6f26v7m2ARNBSu2fhVFpInUShR7VDqQtoHHAmMc6VkamgLfGzpyaug0FxTFa5Glq13Iut4QFZCh2SRyOvevYVyZytUds4Lxx8NW6n1phC5HxRRqDNfomSIr67wxZ51kFmYuY4vpo5UKiJR8sPsMBo5O,W,UXT8xvpSoHd713ROhDpQNBwdBVkbDEhX7eLAnOAWeg6BqSZugfwUMX19on1ILys1a5pTTNsrIxLgZjRorenlQBN2DVHLcJSGos73JajWetInk9QgPPccz61QVhe1AFJTcph1yqzebKWmbkdavsD0EkEYAFTQNNdrSjgPgLmpOeCzHDwrRbDoXN56gJq5N9Z8eRmflhn7geVG9iMXxIUy7jtJlQjUBzIhcCxv4d45C5Z1BXiOixVQ4jUDHwWIdpnJ,hSoXA79ljGdueUi2yezHORNeeCzkVMdINxWVtvPCrlcJa3oaDboUnvvkF8QoitpnS2Q239ZL0V3gethHMddET66kCK7Sy5ekkc2jmBIfTz16t5HCU1hjNAiu99QB4j1XQBA1inHmZbudXCq8d4HD3GyP9y4bnqXRwwGswLvAZNc7suj9fC6bXFtT0NTkJZwQaxW5vCE6CnCjkfZbazixWGcwOgJsevvhxPKU61jiPeI5piPnVxxmh5StwgJiUhkt,9VNtlZuYCrgBzxWWdQvV0ipq3DrMlOSA8BjqKmFERar6CxZ0dbswrdbmPFQjuRjpnrvfBw4oJCdRjt83GqB3L85MptLWZWRqksKeX2wrQ69U5Kw4XywVqGAmoGB7ZHM0cxKS0ixePFhiuOb4FcSPYDJ57IQwvLxLn2STMzIOCd0HnmS9B9x8O1fEjVvfjb1NXDZl8cGKdv0EI49Dqc70X4Akk7GhUc0QpaeMnWDTEmq2E85UGGmWJTfP6EdcdtdG,DByLXDxbGNQpXW30tFEO8EvJu7TASwVCqhy7TKh3tYNTB8QSrdylgZyPM4pAlJktk3C4s0fjMZmhiBwieKQEfmNfaLhbLpzsXUsfWwJkLjhVlZ3UPnhf8yNZ566hEPbu6THjWR3WQZ50Bo03iGGX2NJGqM2TWHTsBos0bWZGHSGEuPFmaNYOBHgjfm8gitOqfaBkFTH8o3tVbcylJxnE3kMF4MigcHL7tqJolyHOVFbNTQB1HAavOlcSewaPmtO,R,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'
2017-07,-24 11:03:08 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-24 11:03:08 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server received (7310 bytes):'
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server received (2504 bytes):'
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server received (213 bytes):'
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server received (3528 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketD,idDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server received all data: 9AIrWJeHWjMprn2cll2l5pkeVPylaUZtxklaRHJjA4vC4TlBzmIA9rQ0k4KNGGU4a9uZGz2Hh2qJlwS5zCJb6AavoApiADF7Yt6BjhNXdtVyb3oY7Gafq4c2VFvba75pIN7pG01ospzDNgxGgHdgpcrBioSJdG0AhLPy4wgwVrTZGioq5G,hNPho9ldqAmx1ZKr1i8bE0i3kl2dT6ZjuatvQ920keUWPjqy5mvvoKg4w7S2jKQtCCNp5HUrLZ4Xj36thAlQfDIoohJIUe4dy6kmiUPMUWIsEKmLL1euDzh4dwdayRmPYdY9B6RICSRr9DiqMx0LAc7NhWuTL5mjQRjuTH7T4t6uZMuNrQEVYKFoxVEqg1qiEHIh39MvpsqXAuZrbHjxBJStNX9IYJ7qSIVehtr0vWsqap5daivgJksWAZyPNPZz,GVMQpE0hX678kD5NKValyRoAPupOJ7CARSNhxy8uKknKqhFg7rsELTr9v4zPihdEIrVG89bLMckaOHykJAq5dBsUjU7Glh5w1QPMm2ZYD2iZJhfkA9jfZFkFbh7b6jFrA257NN0vLKK0xvKkERXgkFhL6aJRONaHEd0oWMaJiQUgGvncfoHo5WRiTsmBKTdJOFfyZPzSGsheHyjss43HjVmsrRBJd0ZTaLpuuIPUq9qHQFFwCUF3Trz2LS1xUk46,4F16EKGINpNEP1R4NR147kwQTctgKlazrkLDDrubLeYMq6athf1YbVFrJ2GbBSiTZQlHI6SgCmlKTdZv9bQDE9LGjVP2SdHdJ9v51nShdPzngDY6Sm2vvizCHJnNyPBJTE7iOGCpeLKdpnNygEP9kM712nGogydEVstPdfBwewKmg0oQCPh9MoQF3ox4cxBVCxMPyhjB77CXljRwWncTUxYAfT2j9VMOlizg4zibnMbTJyilMtyCQAH6PP1PcHW4,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disco,nnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
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'
2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server sends data back to client (1638,4 bytes):'
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:5 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BD9F2C7A,-F67B-4FF6-92A5-D205EFC2A0B6 error: max retries exceeded
2017-07-24 11:03:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1k04mhUP2nvfesrGDBZO6REI6bDApzRW","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:03:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1k04mhUP2nvfesrGDBZO6REI6bDApzRW', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:03:10 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:03:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-24 11:03:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 11:03:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:03:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5ACAF211-0772-4AB0-B392-E6D7695E2A89 (syncValue: UXmzK5d,JD42km6EvMKjfVqeLARvXUyOj)'
2017-07-24 11:03:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:03:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,CAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:03:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UXmzK5dJD42km6EvMKjfVqeLARvXUyOj","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:03:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UXmzK5dJD42km6EvMKjfVqeLARvXUyOj', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:03:13 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"5ACAF211-0772-4AB0-B392-E6D7695E2A89","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:03:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 11:03:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5ACAF211-0772-4AB0-B392-E6D7695E2A89","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-24 11:03:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 11:03:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B7A64547-3C92-4AEA-B913-F34E280DDD7C (syncValue: 6fmaOFr6vaWEHNSctZ6Yypv,UuLR5b3fH)'
2017-07-24 11:03:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B7A64547-3C92-4AEA-B913-F34E2,80DDD7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:03:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 ,1,1:03:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59597
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6fmaOFr6vaWEHNSctZ6YypvUuLR5b3fH",,"error":null,"portNumber":59597}'
2017-07-24 11:03:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6fmaOFr6vaWEHNSctZ6YypvUuLR5b3fH', error: 'null', listeningPort: '59597''
,Connecting to the localhost:59597
Connecting to the localhost:59597
Connecting to the localhost:59597
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
Connected to the localhost:59597
Connected to the localhost:59597
Connected to the localhost:59597
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [6, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [6, 7, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 94 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 95 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams,() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [6, 8]
,ok 96 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [6]
,# teardown
,2017-07-24 11:03:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:03:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11,:,03:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59597
[ThaliCore] Session.disconnect() peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdve,rtisingStateUpdateNonTCP registered to native'
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:03:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ADD0124E-485B-4CBD-9E05-99F82050A2E9
,2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:03:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:03:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4BE7335F-67BD-401E-B0C7-2C7A07B5ECA2
[ThaliCore] Browser.startListening
2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-24 11:03:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
2017-07-24 11:03:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8DB5C8CF-9F6C-4FCE-AE67-31A370211A57","generation":0}'
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8DB5C8CF-9F6C-4FCE-AE67-31A370211A57, (syncValue: adLe1qQHkQiyPg30boF2yxuvgikWI4zJ)'
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A3702,11A57", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"B7A64547-3C92-4AEA-B913-F34E280DDD7C","generation":0}'
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
2017-07-24 11:03:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2BDCF5F5-8C04-4171-800A-A898BAF20B04","generation":0}'
2017-07-24 11:03:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:19 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 11:03:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
2017-07-24 11:03:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F591386-896D-46D9-B7FC-0F4D50F2F645","generatio,n,":0}'
2017-07-24 11:03:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-0,7-24 11:03:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8D,B5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8D,B5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8D,B5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:8DB5C8CF,-9F6C-4FCE-AE67-31A370211A57 error: max retries exceeded
2017-07-24 11:03:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"adLe1qQHkQiyPg30boF2yxuvgikWI4zJ","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:03:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'adLe1qQHkQiyPg30boF2yxuvgikWI4zJ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:03:29 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"8DB5C8CF-9F6C-4FCE-AE67-31A370211A57","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:03:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-24 11:03:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8DB5C8CF-9F6C-4FCE-AE67-31A370211A57","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 11:03:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:03:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2BDCF5F5-8C04-4171-800A-A898BAF20B04 (syncValue: 3mrASg7,6JkBffPuoDOyTOdH6b91hURFh)'
2017-07-24 11:03:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2BDCF5F5-8C04,-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:03:29 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-24 11:03:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B2076B65-0D70-4CE7-A471-5FDF34A76145
[ThaliCore] Advertiser: session connected Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B2076B65-0D70-4CE7-A471-5FDF34A76145 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59615
,2017-07-24 11:03:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3mrASg76JkBffPuoDOyTOdH6b91hURFh","error":null,"portNumber":59615}'
,2017-07-24 11:03:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3mrASg76JkBffPuoDOyTOdH6b91hURFh', error: 'null', listeningPort: '59615''
,Connecting to the localhost:59615
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [6, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:59615
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [6]
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B2076B65-0D70-4CE7-A471-5FDF34A76145
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2076B65-0D70-4CE7-A471-5FDF34A76145 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2076B65-0D70-4CE7-A471-5FDF34A76145
[ThaliCore] Session.startOutputStream(with:) peer:B2076B65-0D70-4CE7-A471-5FDF34A76145
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [6, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [6]
,2017-07-24 11:03:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:03:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:ADD0124E-485B-4CBD-9E05-99F82050A2E9
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59615
[ThaliCore] Session.disconnect,() peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2076B65-0D70-4CE7-A471-5FDF34A76145 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B2076B65-0D70-4CE7-A471-5FDF34A76145
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
[ThaliCore] Session.deinit peer:B2076B65-0D70-4CE7-A471-5FDF34A76145
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F4F5F622-E47B-4CE5-B8AE-21666B67C798
,2017-07-24 11:03:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:03:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F401DB5D-F313-4E69-812E-4D05F31E1633
[ThaliCore] Browser.startListening
2017-07-24 11:03:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:03:33 - INFO thaliMobile: 'Received state ({"discover,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:03:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
2017-07-24 11:03:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F591386-896D-46D9-B7FC-0F4D50F2F645","generation":0}'
2017-07-24 11:03:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3F591386-896D-46D9-B7FC-0F4D50F2F645, (syncValue: dEJNUqlTAajrLTqnO84JSdfxn6FWd3Xs)'
2017-07-24 11:03:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F,2F645", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:03:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2BDCF5F5-8C04-4171-800A-A898BAF20B04","generation":0}'
2017-07-24 11:03:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: 0)
2017-07-24 11:03:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FA2EE142-1A99-4149-AB82-FAA6044948AC","generation":0}'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:34 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"12089FF0-3ECC-40A2-A184-6C264C0E4B6C","generatio,n,":0}'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-0,7-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3F591386,-896D-46D9-B7FC-0F4D50F2F645 error: max retries exceeded
2017-07-24 11:03:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dEJNUqlTAajrLTqnO84JSdfxn6FWd3Xs","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:03:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dEJNUqlTAajrLTqnO84JSdfxn6FWd3Xs', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:03:44 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"3F591386-896D-46D9-B7FC-0F4D50F2F645","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:03:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-24 11:03:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F591386-896D-46D9-B7FC-0F4D50F2F645","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 11:03:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:03:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FA2EE142-1A99-4149-AB82-FAA6044948AC (syncValue: nXM9BST,DIZqdWd6huUXZsh17hdWdki5z)'
2017-07-24 11:03:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FA2EE142-1A99,-4149-AB82-FAA6044948AC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:03:44 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-24 11:03:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4448EFB5-325D-4402-9F4B-B3F19AE2501B
[ThaliCore] Advertiser: session connected Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4448EFB5-325D-4402-9F4B-B3F19AE2501B state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:26A39883-A498-46D9-BCE1-537D2CD964F5
[ThaliCore] Advertiser: session connected Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:26A39883-A498-46D9-BCE1-537D2CD964F5 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59633
2017-07-24 11:03:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nXM9BSTDIZqdWd6huUXZsh17hdWdki5z",,"error":null,"portNumber":59633}'
2017-07-24 11:03:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nXM9BSTDIZqdWd6huUXZsh17hdWdki5z', error: 'null', listeningPort: '59633''
,Connecting to the localhost:59633
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0
Connected to the localhost:59633
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [6, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 102 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4448EFB5-325D-4402-9F4B-B3F19AE2501B
,[ThaliCore] Session.session(_:peer:didChange:) peer:4448EFB5-325D-4402-9F4B-B3F19AE2501B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4448EFB5-325D-4402-9F4B-B3F19AE2501B
,[ThaliCore] Session.startOutputStream(with:) peer:4448EFB5-325D-4402-9F4B-B3F19AE2501B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [6, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (13140 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (14235 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (12045 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (14235 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (7501 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received all data: w9G6TnMK1cipwok8fpulwkkTdsBlxwSKaHE0UVDrkjl53D6IUznothyj3bX6d2kBgWXTeUwYpYCUsmdeeIYmon28ic9uj0qQ2z6g43xSzi431qt8wdVUt3AUd8eHrHFeK2AYHd78uIfLtI5ZdQeEphqWk3hGl6R2Wz3HxpJYKs4Wy525l8mmv6nmpG3ljWpVXdYrk7vzrELdfTrfUxoXk39a7bUbqz6k65KVtajlh6C993iLt8mvLuiZnQxay4Ev05GSIZoCa2us8uPJeixIo4uiODnDxI9gHEjaiQSCJAqxbWqmVeYL1iQykekHfKDgHAZWv0bI8VUK5tYYw3xPl65tcTSP4YENqajrKhKtByIkVWon1i0Wl9rM30LgEC5u2tRsh8gUA2VKLAjlyQ4LMQibZ18cLKebrWsTuw9yvxVvV8usVA,rOnuZxQ1S3SpTGCUtLeetffpQHWWdi1wP2fpmouswyp7HhuPCloaIEW2Re4eg5Bnu2qe4KeyYsFEDCYT8q0OZyy84Zwh5dETAvP6EPjwDIuqUyuFwpSAMGVAqyT0JriZtiHd6cjthv0Sfd5vo0VJwDEK6YWOK9D42F3OnBYwETKAIVSwRjT7aBWTK6E084Dk3QJ1SzZbOVgdnUDf2SpyZRvpLuDQtGgtA8QsGI5yg6er4IEfxJC4rS0Ar0tIjZyu,X7lCp6kFu1tWwHnzgOXxOoGOrVVb5I5ZafTVtprAvyiH4qUGsv4q9ebpEEkH1VPJdLww5Fc3IGO6KqzK2hLwrHKPWZdn2CERWSpRC512tZkag6q3wgwUjGE42KWCaeoIwOLrOYklcFdumePmUDR3QEQoYkO8yolrlTuNmFUyb7wBqfWcYKeZvMPJrM8Ca7Ujv87JwxYcCz7llZEX2eZ9ICpIPj0d9d7QvRFCqB3o0VVd5Lh8K60X7oNcBKqIxG0D,6oS7KB9OEwIRcH5N6u8YBIfVmephcLE6PIQCQdoqCMlpfMCkcx0T6UbGkyGXDtbUNiI6hLsFQWzwORgwrgdmv1IFuvYeXraQK8frXYgs3L0852SihAVDdw2U16PC2uINtWH15pMH4HFSmCSQaVnGf5ov9QjVOXoV6A2ptGpmtJw7h6sBRRirnXMwRzMxYy8uc13ZIT0JZ2U8tATV1xLalSm6GSF0NyruCqJnysu1Mox7BRtvVPPYDVJsDVx7H9ZY,OoKH0C3J3cnOyusqmTryZYD3csST1cVfnaAflxml0qIPeOcJs1DZ3YSxQpngicDxttgSzZymsm0xygawCO6E8rfwQhJldhaN9cji7bTLcbGcHAQ627NmbfozOtq3FOpOmkbDTjMBkSAoReUZgWgleJhcnjPirT4gqraevXm7oebBKOouAn5O7kH5djV9fCbrtUFdZrH9f58mIPsRc0sBwClL2TENoqjOPlTAgP9Md6tABq85SqzXbzMTrug3w5ND,0bF3NcBfVIcGAq6e3E2u0NYhbjnZHHhfRz3aF3irRz5EBplcFMO5SmIPSahMxlZAzn8QOdxBKic0nZU542vt83bXDli10jwUyIlEWInmKggiwqCkKrxNA7Yz1Ytht5uKmgj8andMuDN0m1wpPNGZ8A3w6uLkdqoK6XMgEg0Edn4vCaFTexTkXWFZ2a4iNgabKAIvbs3YJD7fF5ehU5LD3ilETsDNt4kkgdvjvJxCbvu7mdQDOdzIpcam4zTRSejL,zvOWOtheL5SbqezBm0X6bYlOGUZA4Jdzv3MppR57KiZgVQ59mimUJ7zMMTMoX6zQqTXJuonSuyo1LxcrHy82kTUjje1tGnNfFrUL68WwF8FjO6ub6w869Ryz0bFx5Zt7tuJAol9JjVidJoK5VEeckyWiIM0yonP4hrJpZ2XntOjBil10sOSWYci115KQS0tmiwIYJYpl8QURD2tbqSMLIF4HxTeSgNYJ7vpKgMdk2DaHOyXmw0dropIEl9PKCdev,SIUPgmie6nu4cEFjaaEyK18AgcUSgaAk2zcUG0HQID1g0goPCSLJiSxIxu6vt3IKlpnoEjIuQVWU613bI51ALXMdB0GIgrrNfbDNqdvXvxiduR6yGkx04HbYFRuC5Go86Tw1mrBQBw1fTUkrWJPlYUezSAzdUUir2YGRUkos8Dig2VElblgieL1iqFQQyxaW1AISUmMsorSzifRFPlfdOWsiDpC8ID0FI5zcACX7GObemQwKbbSOt7uiNy9XcyDr,rEAj1JMOZSAhQUJaAkzw0pzvdVS3JMswdatWmzJFcUmA9ES0Xtz7h0pvTEShAs0igxtjCNPos9xWKD75az0JI6R9Bb64aWXTv4ZCJ3WwoDvQ0Gwu4Y9eXFvU3wOIOTzOcQNOVZGsm95JTHPVo6oCQOsVKp7gDdnZOikz3OIMuH3BBX7CrVkeMFvTp3BXCI4VRpNAwp5LNNDvCHw8OJY056HCWggWlxUWcOJrBZLCnXdRDp8cMtQJ5j2hpFT7LlYc,QD2gOf8VCr45VdOZIKi7wUBvaEIehiM0A2hoaqfJbgZPU5DLTdCS9bqcIXhvnA0FmoKdYDsQe4VEG9NVE7YnAFZQZuVyhQZnpP2D89XAjX2PXjaV43spovQEHpZcZG2Ti287dAyWnzMezXVEbJrB34EG5zkAY1bZmgY72oc9p0HEwFjPKqDWveCl6cRiPVnHB9XU4PX3LPBlGKh0sEPx2HeMUFRKH6euLAR1PREJ0RnpE0977UlnyCP7q5EAQhOh,HWEmYgiSycUie7Vt912ZPb294HwYuxsBzgXIwwwYCmxwtaCwmnqeYoSUMVSCinW9ExgoWk0fBOZtHKOJlITjDqSK4nRgjZGNXbUUxvFz2NxnfNyhG4Jf35OCChCX1rUHXSBQganjlO8dHf0YjnuSh2U0hW3gSzJ9DcFoN77L3z1DfbJBfTDORQGuKijLMyAsj7K9dIRX0ZBfiZ4n4O8cguxECyGJ23OQu6S7aJ9HKXptPbd48PT4lqS5sEq6nUpt,2q3wLuUG5G4YvLT94dBzuZ3K7hAzQQNjuBvp4uwYBBaCQ0CjKnjYuVR0meeUJDRjArNzqUAThhsXVSHrVAbqPsj1gENvp0GzPTkCBRQ5nbup0BP0izCw0ud3PadH9F7K91L7UtlLXpdiCHSVmWtuuGmP8QqU1m6NVGvM7JkOuu4pEgUgGs95ueoHU3cFwoQShSPoO4bvnAPyvyCMEyRR8LzFoF5BYkaO4HdVZRRAowzXmPTAhQiKe6UlRlQHCXPA,Hk9eyB233RPMNeoGtSsgg0KZ2m5IDH5jfL0OhhKiiuSxcB1RgveZyi7UYEkKg5thCKCvmgXlZEoCkD9KIJMSbOpNHIqtGTU0aTaC1z9jCIUR0grKzSdWcPsEUBfZV42RXS90GaFry0Lg7jd5WcGUUPL881o6NbxU0dtWLGE4EbDEBtmKlyyjgXXtphlk64m5IwvDzwgliqgIdzwOpEP1NBTZH0SVyjAaMBnXG5dCU59YUAzrfCA4WqxS1FsKEpFR,tYkqdZ1yO6E8HEgs2K5vcBaXoJLeTAPEaXgSkcuiqKBOEo6kNjxtAL7obzrI5xkYcTcd4rBx7b0qzSZ0rVz4J6Mxq1dxU00TrBErGzCLXmwRJLOirpW3OuyyClS4sr1OMFEC2DkUKJIOgZOEKe4sDZ31G5tsxg3Ls9590sACbGi3UMfv96C6cmumlypInOAR8SMc2fs3s7dfJ7ci6WRaXGYgABQ7e0qAgJj3ft7zJUXYGDGa5lZSgSjNqd1b04Z3,8tdPXSLc5fspUrZBQ6kFJvUQLsOvMIbzWOUXBa0ysO6fgyyyI4AONm2SgrZqfLCx75uvgVnNZlRUMJn6se9OizQakFGW2jCfHpWP81nwKNk1qKrQhkRozb0e6XA8lFJu8zr9VzQl3pC3EMqYMmKm0cE9sVb7V1Q1haatQsD9YATMX0b17CGK3StdngYysGASxacGVP3F9NZvEzDeNsv4ir2mX7VMAihsiw6HOJhxIPh5ZpsjfxiKUXkhEYQsZ0Hn,wXcwX66Nl8VFoCubiPbHy8xWEbtJxX0CHQ2q3tQtAJg9utH5fFX0AKkl6lV1yEJFNnG8IwX3SRkXZc5TMIvLF5qGJM4zKE2pMm0J9nU0MB5MMX6Foyytmz7oIVTEiDSZQ5PUyky3xbNgZkenqcHjnxM7mcOlCAOBVMq3i6sVmCXBCP3q3boECHa5mnYUPdqDSp78FtNswemsrh3cznL8lGkushHmgsMxTZZJPvFN8OW4fJEr4LdWf7BHRsuJFzgM,vMOiGm9x4nKWvflS1GhDNq3G7lNJHDGDjQ4WExdvDyncDnfCMfYa9yTcTdVfwhbeU97PoFEkndV3MadiaPU10dDCFbSGe7Or02rRYU9h46I5YAiDK290XvmwDUuQTsn7nzWMNRuHdQOGd6sgGg8VlwHGsObqyQOVFTpq5bTK2kFp0efQRjJuJxHD9ixZDEKSL1OvkgunanoDaPIj5bkKNYm0997n3fYDVly60YvxwdKi4bE5FAoONEQ3qHLfu52R,M2rNvtJ3xMe40YPXWEtRHKDk5EykVJJwdSby8wQ84xBj2Njhu9uY5eIvG1p7NV0HFhwooMKa9T4EUx4NwvkosDGKqxYkQA6rdLie8NV1zADIwnyc9yXFSUeRAvE6t4giVKi4Esu3qLMQkLOqHWvYSPub0HlAok2CP4k0G0uVdbn5fkYW1igGNa4FreKauGIqi34uUmtIDQxc3EqmqwRgqEG1ViPfaV7DtAK28EjpG1QcF3tJ0MEIzYxRzWdhZz7t,H8eqE1zVyEEouDQM20jw3hN9qYMCzcOJxYwTX2fhxkcTZcWDmgkddfct5oNXIRF3I2QLYFntcCOqVFdgP36juOVL4XnNp6o5Cau4CMwm8OXPudTVmK6uvxU2YTdr0Sih0lIP0SELS41U5Z3ZuerMvrbKUvfv1ldag3xflpfp7JgawY9XvprIj6GdwX0FUltmPO5dnZNoXJOj25YuIpmoD5Q0JGvNfrvuAyNvvwQlJu58aY02VRvbJVL0H0dLqnti,iZjhXfUF7HI82QxppIQ0jvnYwZ3yBshHWBYY5utSw1KFFASDQT9qeCU6aaAHIGyjPOPOjwF94Oj6pVcI41p4ncI7SMFJzkEtc9pzgSxyVgtGT5ww3VypB6r5ZzcB20AJAQh5X5IdM5Z1ombobCKct8zA2ZvS4MQ6EXLWkrAr0SIJzKoRlBkDi7lMCuWJyIsG2zia7Dg99iFjrvaLDsRqZXfv88sXBRwmaaS5XiirX8p2C2t2BC5qMN5wXDh1nlVy,o2Brs40POmqnojd5jfvJWhuvJsrmdf0CaxKL4Y0etfhUdpBu0wuPi71cTpqhiYKSFVg5Ec6iZfdv1dfedwzisp36eb9jweusDzytUHq3kRvAPY0eOhIxcSkkrVREvLRvj04avT05vuldkzHuYEcQ6xZYN7dlIHpsrQMWy6Wa96NTgJpAMWqsYXYJzwMBZaVkTAGPuHRTUSj76M9xUgllCRwT2Qn0kifwanS7cyveOIxHqSBhp5n7dGFrmniayX6g,ntp1p0nn5vBHTn8t02LDQOQp80Yzqk471aZeomDD2kafFNJ59DvZS7nifbZLiAAP2ljaPgAZ2evL8VTyIcedD6r7oXS2fr90omtDtPD7RnDD7gVdJaIc7Ex0u6ioBoGO3Lc884NEpUO2fBiJJ4WkNTAQVjB5aAbOLa4SMRY5yhFcbEWMhwuB0unpWsjWPpoPTd5BudsJ8Zmx6cCVZH64aE40GhI9MhCI8GHLvrjQ9wKUUV6JBEupAOc5UCeBh6JN,TaI2C8acA5AhlY1EyFWgxtUTiGadhk2XMtHgG8G8hqGvnj63Cb32qJ73y3eWEixlQGATcaTpX4mLMMwaIIDmBWk9dt8sTfbpmbNuvbVFQfXsKA7wWo6lglV4No49g4sRWP8MUiatRc86TiUZFyuXd8pYmTvtK4dRciDziCvbltaHUDx8ajDerCRhuNqJ61VM6K2b2kZH8myxK45IYnkO9ErivgX0ByFj3U9zikFfqXzvQtPrjtP2EZPhtVSlPcn6,jMTh0RgMdCp8PK4frmFxOsjNQpquJLKAE8yao0xGKwKriUr4IymaBNCduU8b4iIxIGD6ZfDS1nAYdB4RiRpq7oJwDzJNU7w5265bsm4TnF0hI22zNLeToHWHOsOxXVnuyw6pvorifoxIQLmxHlSABebTdPngQWo4RSWBt0aVS69CQum7DS7HjaNBO9GhHIKO8XjWOj84buyMSPsaU1LU69Rc3lTmXzXqxrisRwkJz2tPdjMJRGeqAOUgxVfDcDTe,7jh30lk2BjFqgRcacnnjE5kvzfUKNMAPTf6zrFwUEfs0tM6A5brYgff0yIOZ7zZe3fuky0hso5jpmVtiFkXsdGtTG9fz2djMKBSkC5TWpag7aY6dyyIvHnjW8se7nln8eHBCp9i2fvFDCPhvx0hwDFAy4gOcPJCuxBgTBYOsu19f9HJGGZTH7hBYdz6fjt1ZQgnoOnm5SMOOpqPgkBbRKus9gc12UzSq5BRSYnV4THrxYE35sIp0yrv10cclFUFW,PlnymSlHPYkDHy1ciOB1ngf4k7C7ZOoDTfEa9VOi9zL7iVf0BJRsZivTpWm2ABzsp7685j9HgHoEFgwZwEyNZaWPTJBVKEu3Ny01QZgfqMfAwnuT91Nw9HWJBJu47yivDJdlSTixD3Jgv93vP8iIL3FCYez5x8bKQDMLvHglPcJYuSPTrl4uWx71O1XgBUJAiJNzJ5lUjXCpWdtcWxaNANMREEjIVMekUaEgmJDGw7Rsr4g3Veo5jWRM9lR7nPtJ,NKuY5ErkvgI2pmyRizSSLEL88FXazaxV1NxD82lt2vBB5ws6yEMuF7KxenzZdIhd0y6vhb8jMghgykoFhRfOGS46EEDgxEU6wBZHsMFrqHkOMjFpDgsDlKHzeUPsobacsVma2XYy6PzWSa9k9hfHH6OLg6KTuPjKTuFP1g54Z0GEaXb2dwawHnyyUQuIlgHHx8WYQ8iSIYOXMUgy5ugvc9uy7tXV6ALJc5s9OAA6UsSJ7lYmfen5kZvF5EeZbc7V,oaKvo6QkYncxX1OfFJ3yx4QDmH1KPECyIb8GbgMHlHtX98mrZjdTaqQs5ZFM3sunPnjdQQ0VaVKnKXtZS2mNVL0VdttsEGykVRYnxwWH4LuNmOvSOSiw9PVcDt1DaH2bkpIKD7BCqPnTBxHEZWzxBrZiv2j29uVntlps49MLIMdNGGWr0QQ2AGupTiYpTMf4unl46IE3oZVvFtWgnmDPtg6rSaxFzpF0rrdCoGY4mTlSFXfO6eJzlsuJ59AEedoM,UJ2m8J9DzqsP4xzEgcaFBBni84bpXkBF9hHiJFiZVuIlg6qRFylZg9eI0L1Y5NzXvIzPSbdJYoDdOcf4EDfvlrNjCtdEOl6RDQ5tnQkw3YJLd3fLxuPJO6gZnMZF9XIXhsTWo5vu7s2LC8IPhivOumisLiVKbBgKkBKMQSqOk2ujtI5qqazsli4kiXOOcQ04eWyvHfKxEsG8ucTOTkmih9mvhtNG27SZzg24AEFe1ruKBdiKipzV3JS9Dmmp39hD,q5VqM3fWmoffa5J481tmfKZBt7ltJvNlwF5jUmLIZ43Zjgox84sbo6zOxY15ClIVKDeB6Bvn4zds7EGj1TFwwjUttHTMfy5hAJJvFWff36gsQJbPBI0miARgjTugUbiMuWGsc24ceDRl71sd5BqkaEdM5wzdLvqT2t0drlnf5BBJ8QCdMAYGGlAcTIbdkJbr2Ac8Bi5jXltpLxGRaMQVQqbrbLNorsayCDo7JGTpmkDKNZUChvzk2orS2P0TcmmT,84NZXljsA7tBzcvYTbQg2GLa9oRSyMUoybOUhfWpR2cE8HSijYYqWVkBOveTyjoLpOxl0g7MGhZa0it0s1aDv0vFpVAvRtKfOHmAPS7moh0zgGHDxFVV1DhKMJVinCuh8GKxtzE4TjJnTYLddmoiMNdG83euyHy9vyKx7XEtqBa2nV0e0RLDhVCwiix9O0g72Jfke2byasrsUWEm5yaQ8rY6sSzWstpCxw1xO1XqCxS8pQ10JkSEGhYaZkMup0iR,tZcX5RlMz2pEDKRmxeAYi3LyJjCl4fUspFIfawAM5ftgJk6br2vUgW8xbvvWmxjMV2fh78JBvgiV5OyFfu9Yaah4NYT5WZuAvPFIoUS3PGZ0Kbgnb3VPmvIdeCE5SGpDnADrPvSC0gbDM6XtTV9UC5qbLpdhpx7dyXTZM1E0pDDbRjSDGKmaV1LtP42HSK4dIDAvoLQhUa580dJqiODZ7F8H23arMaqBVJmvMp85F6eQWWqrjiKPqDMO73pdDmRB,cz17h75hKn9LDMAS4QWnX6pnWQZ9wEn5ZaYPkADGdxSVtwNdtr2vLsVMAq6L3VVVq7sgPsDmwKutvYq4JwqXBa1d5qLBUQLG8NNdDprb1REao0HHQwaZ7tIDlWAg7fejZk2w3upXXYYyikYk1IxxBIHx1d8UH4GFrfn6koUK3oVtguXSYHzsHuGGp4BU9XplIsmO8kaUftpGWvKVDbT9Mmh5NLnHLUgJUgEgo9gHStZy6RAquf4O8x2opioaU128,H4QsMDC52XNE4Dt6LQSpRZ5gfXMX6FmBPbsKBcAcA2t3RFNqpii9M5XFP4e60brCWFeG0XOaZaq5bspZUlukzYl5unEyNkADl8NRefzEyrenR0jkwQXZt9ekyZnDnxxxu7dvyLHcopQZzexcMtoKnciYHySq9cbXDeMDlxxbqYdVoYbk0pfKxxWLysVApCL28YbrTBFww4Qjc7o9RmtfAy96R2pY3lZWAV9ClMyaIZiHhmXRu2u0znRt2VIRMl8V,dfOtVDmTSuYsSYnjYwYAfq47OWajCAoSdRTTfc18aDRGzQYmdDTOKrpp3rhMoHhntRlpI3bNWfB4mdwuLEtXoVAa7nssskzstO1fKnaF1fo9zSspMQBDpERTCGp4Fd513fmR8Y4txIv13u9DPD6HveFcglaUWzMIure2zxzx1QB9uqPc5JZ3c98HqVdTclGYp1wplVgqYDz61VF2M0cGhe0OKz0Jh7hnPUIY2JWacsnX0PyOBEDHRxoHsSBRieZH,QJnyiKMH5tpXeEsqYchSoELuIusR2RxbUtyBUdASd4CkhxamKJhKt2lzshBW6wqN6WyWbCeQmvJ8z9OSTxT6h7C5jbQStFLmCLKdevWSwjuu2u5V1v00lUcecjNWXphDSeGwEziPhAxZj8xldbnQAtbN09JnIdPer2AiHEvyDonRsgLTTQ9fC04RxPRQbmQlnboPaWrCenLRlM4GpA6Fl2ATUFCYXnck7PLp9KmUOFoXPNnPbvjRPHLOCPwkLTP2,0jSsFJ0zRIboRRbnOQbrx121I80YKXXYcHpP1v1xffaCZfIpc9hzHNcOBfxWah9zFexqVvxmwNhJ447VRKgOrqcOMXQkJIzCRkR9Yhv7ei4HCEzYZXvn2isI2R1mMPE2xvPIYWRa3rw90T0RenmUBS6IkuVRrc8Lo0RdwkeOvZoNbCf1ymuLMGOxtRP0oDtHmlvSWpJh9mZYaVebfLmRAexdGT8YTEQAvS8NqskPl3yQKc03LFHdVs14yGfY23pA,LAdH6nrxlPgKatViQaahfJ0iFw5lE851B7tGUgvNX5XkiY1VG5QcCyTE80dwhi46GaF4aXeP5aSVEx8zfj3OabZ74Y4H26Vwg8oRU4pgYaBVFQTApWP4OGagMOGrK3SArIwcwtafZAHLKenOtExyfbbSqHsXzVaVCQCx7nm77Nvsc0oOq5jaIfEKVaE4ohEOz9bcQBX5H2qJZDRqQr92OFyQf9jesNixHow0Xh0TRmKWX9JlfyPZIL8n0bQk071x,9rnkRuJEP8LgiW93m03UHWNyN2itHGSIc8KPyPj5v4qfwFBzAhAFlyXQp9cZuVYBXI2PL8yONAxuOOdYiRbQK2Mupoqdr3CpOgMjJQtBDphDMEtV5YirGzJNl20TWbBMp03Gkhw75Kpe8IFO3Vf7oPYl8O5UkNFYGto4RAlwVJ1fPxTvOhXdTlSTwBHxVJdgqprg5tWdpG8jUZDgO4aLtWoO9u732gPMh3GjFe6lJXOd2d4Zn4eN4AJiZASX6wI7,n3aRVzIj4XKNSnhH7cuigC0diU3aeGfYhrmagszqMLAS51ndht6KdE2uy7ozGEmVKIOhkBY9zzFAVkiXDwTxoqjbHMRGvqHbhYNz0CqNoUw64XeTeMziASWm1PkcyjAD4RHu8pJntGlfz1FVZvPGHj8zZSh1vxEKdLVkAKm5hK4cdDennmFpzt92KTEMdmuZboxwo8A3XBwlTDkFuHEaF2q1RH0PCjMAremszGn8QCl0pu5sqtXuTSdT1NKom2yv,kMH0RDRDO6DIML1qZPUHc79fgCxma2hDoANbKVtMjQPmEPVYUrocaJBJ9fgmfDVYwqjLWkdAkGWpOltiwrb5kU2QfPNnqCyMsSvgNLupTraNmledfrWoeFfadyAAvX6j0fn941q0w7mq72gpAUicQ04bJLNcIx6C0A2qSq7qF6PjDFXRgfYWh8t3xFDwwKOTHupWgLuaO1lFryCUPIQpB6B5s3Hg5rkVdoAyWLrBlPrdoj7DiRqzdPvCLf7M0bEN,Ok1tbt6xfNuzhARfMBukV53dW8gmQjrMXMY0J2zNmoRlsX8KkI9sd6Kuzo9iFLdAZTQhGQY45rB3FISSll12RnrP95Fl5YIf673PfGwf4Ny8vOfC3bjSjpVbIxO1Nd3acuLO3184sBShTvjsrx3W7fpxquP3YIfa0BHMUgmMaH76Gj2u5LB1Mpd5tdxXNkXjbxoKWQ1IIiBGckdYhAJwu1ZGguHHN48B92nxU3SsB8iGoM25LuUOdJkhiMpueHBp,5PXCAorbiEXcsFxl7Cx8cZFq0C9RhOX9za3IsNYgxEXNAWahoSjcvKNaRnTbHA3rV2mW3q51LeFej41YII1hiyAp1fQUdG6MFQsaj79UwpS7eNuq2gpQtvPchbJswIn1noWGBhFOLhJD8iJNpq4Hpuywz4UkGUVSI6nTftFEM4OAfK82mKP8DNuPLThs9roT7j7aOxO5P0ds8ZaP8wSYbCMwj2vgKiHMrx0OH5DkJb4M1yUSXzdIWILdvwgSYQKG,GxMQlVZamXQFUS6aNyxDHJVGhOmdx17gCIv9A5ftOliboNeYQvbtf8yOIXACoHER3etAUcBJXp1uDh1iK69myj9B2x1SjNk7skUEfbOGADOFI1MpAw0hx7Ny19taOkefppAlmCglGVdLeHu9p2cebFfeS4LTYhWi0WEREBmdlFwYLoonBIwiTQZz1YiYikFy44ie97qppStpGsL2TU6p0QmxODBwNU1OBtwSE5jTVcFisomLzMVaYHXUv5JidTip,xuBl37T2EECKLPkF5va2oJF7HqGk3UXLBA6y65Tzr0orSHyK8NBAgbtsz8uPVS4yBxgxJSoxbX57gaYe0TyNh9vtwTGv6AE7Rnl7rBGQyu5mOw4M07lCEa0gJLFNBS2VAGR0YhjeMjET3noNftbQSEk6EX8voOALj3jjdpzxeCxROp7TVQJzHErT3VNS3IjwQRQxjJYJKCnolb9th9J02CYsEnUBx29kKfP9sY37bFVrIdbZYXxnj2rc7Nc9QBlC,vigQFeF2K6XBJ9aZqi8lwunEq9ahRJGy7jFXPLxF4N1trYvXOsdqqU4lcaVKNtFoaFKXXNxK2iSn562AQSha1BWiCi5STFaM3ptA5yqk7qXl03J2s456sfVkWcmSvadEu7bX2kcZVg8NRe8imysZyRhoFYqk9lWh63JXptL8wrjhWlMpJfww2navDZgqAP0UJFT5a7OWXD07ctPKJoEJfUOIxiBw2ovCV4SviQt7LUVyd6um1d75rREsXkGdf1sK,6v2es6s9ihjaUQwe1Udk6u3s32mJE6QoFvKGK3ESCSOZ9wXU0g2AFxehaj3WdB8dvGjMwItoDbPoavjISBlbBe8wGfPOT9n4HWCxotcoHsAhRqm4eCqm4ES9aL54Y0OFvRJ2wYWpjbPzow9g7puQ3Z59T5cURvZwIaU7BTWrZfA753AzqEKI6oqvEChj8ywTml1S9wNXLQBHutaSBcO2ml0TCgsY7Wlkqls5rK09Dp9dQEmxEIAgx3M0kTsQClXs,zcCiZh8OnSqwJt90qFOrK893EnpyN02MtTBit48EmeE9svWWnGSWcy0evpMcr6l1GOnKWaqmfoXlhdEqOCMDbB6tVGbAeTYZVHmzfBuGh4qVj8ZXIXRf0pEwPlJNPr6x9UD8KYfQVOH18ll1VMVIvHIVeG1BDIEaA9hc2VtyzwlGB3zxrukES6v0ZGmpOwXVcg4dGC0v46QfhMLPdup1btOsgNv1klC7amiLB4hGpSJj5P8YRedhKz0IbhnD8k5s,1EjSo63FY5Ecko27N1MUj2ra9FYLQD0ReYSv7JtnXrSlksPBYk03cGrEUCfVF48vn3ctkDSmD1U0MQJqurssQRA64iMDswpIojN0fxwbEHGOVdOpqG5s1ZCsDxRdzAG3cDsWPb9pkAxfI2cGmC7eSi3AhMDIk6ujyG2DSG0E3UxZ4aK3jZNT37j4rcCCqf6AJ7yOjDkI4prgfT6s7SKwhGLGgafpZsUqvtFprv3febegyRteDoXq0E41E1NI3zHH,OJmDSglbrpxagESs2VZVbgwtxXIVN9bo4GgkPgAnxy99OkQWcxM1BOqajtJ2qwtT6lwAIEWgt97c9TF1bIN2E47rpTYOdaHZWbTrueo0dZgNj9oNYo9D1siRTlA5s88BZO5YzPe7iAUkxBobUlugLKSRC0WJJ1IZkmFXXJhj5RslGZdhzoosAy5RDDWS7mv41K64ZlUQzWXAzgkwD5lR4uSML6nq6Ju1Xk4JhSZqSt8rCWPC841ZLrTWFHthq7aL,q9yfAFhtrZYGLnhnM5i8vrBQXZN8v1vSEWQ6WSiUD32thhITcVc5qtX4qTymfMkJxaShl5RAlzwzUxrWExgqljPRPp6hsHdaxrSlgjqo1aA7XqdTqGRMIRN3w1qf8mJtHGJLUEhOQ99On28tfu0Hjri01IGb15TwWlpu1qv6lCXiRRYEYmvC7CiixoCN2sWgz1KmCCJIRVw8uI1yKohgcIYJfmAelVGRU5ORUHfH0uGn6ELZOrKhICvgK3d2NzNI,Tgs4kJSjnapYCw7xXVAKqjxiyOfiGTW2z1q54A64PoLSXIPDdYcVfbRbwnc05PXUa1ZCm9ipKi7MYIk8M9xh05bXKXXTd6g84e0jOXzREtVcj5hpEBUawXDxtTafxcglNGaggx9CGO8pHprm23QTzZ8hAQKZwH3xlCkWmNHO9kpy1y10MhJ4fIF5FM7D3pRbbi2f6IEeVjXFUJhIsuOBtABJnRXLDz3sFiRJq2BPtVcUWh5YrhYC2eY8veXBWj7d,NsCFnqIyra7Y08QB3X4IgDNGKFdPe5bP9AZzY2vCIOBtjb062yikuOOkl7MBUINunGBwFIDVZWPMYlip7i5mtTablPYCWYQE2VqIM6vsGfmiJn5hT7kyf5Du5XCO0tEC5Fl0ft87MIPpFyVPkvg560CmfVpbqJSzR2bXpxJqnsD5U2xxeuoQjKrtfhn3PkGYl4J4ghEZxNdT9DAoe137awa5YQ2oB90FZwMpTzRom9W0yg9G8uj1z2ndkyelWAP2,RmQxmBOeNd8MdCXmVxtHPVx98eitpULZwDekPknltRWtVrjomFWyAeevdA0e1rhF39xGXZ1lr4DtMvsTj1bKuRbLqWTTZUFpn7dDJunM6ow5kC2G0yqKUbNsnjbP3WVkZMkWvzocLNGdrnDIV5e1mO78mkXTGEWYrQontnzRpXlJ4usKE1xKQnNP3hykExGZwBW21vFRH4lKY3nCOYotewp96XrY61qTC7XQMabfft4wrPaXe7ELGLe1Sx81K01h,v9PaXH6sg1xm24VoGWeNOxzfbgyhwexTkSqhllGecdzMb0AaIZehGgzbbW7vLrDvJKwPopbuLLf8OnJynWcBt9kWdUeoijqWwKE295P8nkD0kH2zue2Vwkk4yi2EulYu7eGk8yVoqCh9lSjZ1EzCAMHVTkXYbnD9OTnxY9hgdbZZGOlo37C1Jna4AXET6ddcaIEI9DSfuX2bmwaD6KTi7HWEX812b0RXL52Ub4yyhTfTKSX1OjgwWlwxqBuoadrm,RqkQoqlwCeiFU0zBGC0InzmRjANMHzofnnmqQcM0Le6nSEXTYZgAj0Oiimv7oWlLjHLL20D6UTEAeyggAiKE4IXd0n1on5mqFLnolMEfQ8ucvqKCwTtmdIMxra3dNP6fIoEF61zvPi7ACdbPp3m9Pxjw84ostqsywIkxfLivyxexgjQ2VbYBe0cjdnJIhikRMm28CQpQ7Pn5gUCd6GfT4BjrKpsRqXmKdkmp3UnBWtn9pBINW0N9Ze2JNWhzt34K,PNHNNrNkQeIemuW4jeuDtwQ8p5nfJUMPLqtNPN9HXOxozXWQp76mxvRHraXNbVVgYVXNnaxZU8dc8JbwH3NnN8H0WzWaN3XDyN8jHojxDpHOQhNSs0uYP6xj6kgnWUr3rbcwlSVqiIcuVdii7FzKQFffcAOdNkucGObrow8hcCioL9JDTsOXqDVByszFwWrArjkTb8p3w2xAvqobyiL2TWbd2RyOO9ASgmomaHvpuAgsPPArzMTqLVam4pvCz4zp,ZYSl4VhjR98FWE3Vqo0005GHcr0VZN7af5pB0PliWG9WvHOtdFQv3I7GZOSupvbRWqoas6RcOJSH9jHaZb815ny0JEyGGpQdmUjAxr4k214W6wrkJYWxh0CEJUpZhA95U9hLmobPcyrKnrQimMvbDGG5wAxDvhuEjCGCUCW234ZZQqIfYISwwuRpSeBS5bwWImSjtUlyyJ9toTD3lf8Nrg6gG3gMKsSViRTPcqPqUKNu8CwG1ASWW2gez5aeL82P,WRVMe92wGSjiKDJbZnK3fznFh0S5XowBUhp5S9gDfiwBfxwX0s69WxjHYGwKBdQpdDSgZmvp8lPQ8WhuXr1ic921I2RY8CuNa3V8RPtFUJHggq9VHBaloqLDU4rYg2D5gD1ZwRDNKDbaQStxsbLB9GMMJv0tg2z2Yx0YGe1O6eyt4YouEgm7OaD9K0IQtuZvBKlTyrBPXbcDIw2kRxPfSRzasbaRpmWsxeFXpNJc8saYuthLUfDzISfmvk3o2Ton,nx5xvcQND1EVBR5fPRykls6vwdGYkH1ewMQVnidjvdnAdcupHKnbWqapxUD8MEF3qMjLdHCIvQgfy8mCszCslutE4vMUIW6aPHwrOR1W5AKyGZbSJL4NYVxJLbY9DHTSc3PabfwaCx3R29y1QkRU46WRqgYjMA8124gwYmxY3aajlT8YA6Vpax9FoiiS9MoPN8ZjdHiAJyLNY6rPXR1UEONqJSswEOcZ0AUqR7X7dn7PVrV95Bo9o4cZXqKmCAOv,m4lzCPSuQUyGA7OKH1IP8uytsBvocy1QbtFfc8h2Vl0bZDrR5kqBFFou3HsAuJu504ydX00hnFZuYkmPqJa6QquCVDvq9EpYQ1uFXkuunUrTttpcrzvz4ttxrovGhML61bKUarheGAYJg6QQKSuj2amGoxTXDi8XjHrzg5oeU6xW4Q4PLJwvQ1qxIvsZFwBpxZVpHiFyoHzBZ6V1d2m7TcAvvvf1TItRLBWADYNjhgSv0g0MHxcDpyE0CmcvA01C,JCPPAIVer4V2T90EC35SfmBU3mw85VSOPRc7cU77ToN2evKgaum6xerzrembFxV961I9DcYvyuHpmO0DpVyoScPMUYXfE5kucbiAY01aEulmsnmFZonR1MNJIKGNMHk6G7oL9e9mcNpIj6k39pigdvClbjfLS0iqYg8kNXZevii6qpqqeYvTWuvVBKtTVlGYGs0NWtndR2uDA37vAxC49QfAcshpd3qcksbW6U1ladbka98WFhKpI77tTNhrMtzc,iPREdiZWLb79Mwee8iy8W7cwZMzvjrN2fWf9BaYaiXpjNkPoZnJL6uhAvQX3ScsJcnF2h7qfsnIVxee2F1byysfgwYZeyXawrbWBFB8CzoX56e6cfjDyPsfSlRKtPTn6vAHUfOV6kCmQDcBtfKLz3MaL6mbNycX40rvxgl2Pn1Qiw2fDWv4mAtm6Pcz0Hx3b2z8Yyz7GVbXmdk9diWMOh6QWEZFUewoy9xRxeyU9Q4jJPB4qsmaV4hlMoNFZvzm4,sQFVPAmf2bRZL0hCeKXvAe8XYlllaT0w3oMTX3qNXlIRnDn79YXGADpJN3fyJPnpudIHvyqAIlT72azmGE2baFpGwfUwqvfvtsHVeg8swVfn6l54SFadBOb9lJIM1TojTXdFmThbvvhOiWVYtylZ7W7gdb46CMIrGeJojod8K5wsmOEnO3QiyiyBmfhdvLVA86ysLdq6rnHPoAccIAmUjUo3MRYsr6zq46PXcMez1jFIxAvyil0tmxyUfQKN6oYS,mp8TXdiVoA3m9pyrXGzEfosrBYP8WUKW29hn5WRz6E6czJacQh6Kxq1jVNWqTAkSEligSgyGqnbGUhTe3QiOq1p8OhQb5y4izPvyFukgGSplgrCxxPQqx4lXiElmM5bzoF1w5pyfhfCOvgBIYpjL3loEMRkoMPFClJe0yJbUqs2KXPTCCNBc1j74dK4NoxevmdJYJBviULdi2203nxmq0SdTalgLdI0DclpZ2fFnhDZbNTvRGJxMjLlTDqskOiN5,gvpEs1aMPnZcmgZD56vd2iBFLEXXcLihDqQqgk2a1S3M6nMjq5Pq0JURGMVWqyu3qcBVy0lj15NWOsBqAecimLAgifalEPnoOLquKGxNWagnLg6ulXtTRAReNej9qshMOWf3TzmEdyS4QgenGDg5rpbU1P3Of0WAngMDzd5CmNN4Rp84FErR1o6fZDsufmElcm1PnQQa5bCgdMjK3ku6b3JcuEhwOhYsNSUmyKrpo0rTWqz4A90Ze7UVP9bZyy1a,4Qeiv9RIgCVFJTLtNI3Ih6dFpnDl3XINu1mYDt3E4ksrlCFXmTSzMQ0Wou64GFjDg3d7kr7Ii1OXEPvredlfG2zawc81Tpxse0T0EBxbKdQpRDX7SUS2kqyO9S3TZJnPm4xmKMB3oRFgBUuqvjLi53zGj41NqUE1E9S1xoKB0Salq7EpLxjqAZPlptXuc3EW3NbWMFIACLyjjA3Adi9RaQLwpBuNt5sBrcwLh9b5E9DrhpLowM92l6D3ZctQkGR0,6Dp5KlPJ0WSwzn5TcP5Qz8FJMTlUDYGbhNWszQVqDFI1acNN1gytwqDLmNosFyMnGA8OF6M5rxuH6H9dfyOqAI5jFDJxX88jCG12kkFu1aJHmY56Fqjip1W2rGmr5hKPD7z5xpQISKflhoZvxcWb568QVTbxmuktffRil5x9JvinZBRnnGfGC1lF6rAQM8QA48EwsqTulf3bYx9zduagugbMuSLC6tnNLL0dRSlPPGOA5TsXhUpIm5U0Idq3nibb,iaGqVsMOfciolXXq8kjcmBTmFyN2Xz5Wi4R7Nvc6ZewHr2g1G8DcZZdebF1ZnMt1jOxxpjGK1Xvu48KBGrUQfFNi0g5iyzmffqpNtVgCp0LSdN71i8I33VwKFTy9uq5XCp9GmX6BSEo4MoZBVOU5Blhj1vIrewKYwwHddAHNw7oh8tqSWEta0xBR4tvF3gWrXbR0QfbHNFrjMd8gm66uU6DYmaNPbU0lD3wB3McCElBQIkPaLzXCTZvoEPK1n5z1,SSEspmXdVfxq7d6dh6Lt0jbz1BGsO5DuYKIvp9Rs5IgmfHVl762LdawZ3C77JPpuvLjYWikYmubfHzDfwX9eIYFhcwK3auQhuqBXpRSxlPhQEZStJHOP9pjIFEFk9hDofK8LUeih9OzfIgYkO50BWAAc9j28flQYJLdDk6xaW5e5ehjAaVFoA5EQfpiyo4V9cUehsE3ooPInxaf6c0NsAA43aA5KpvSFnB8Ad9q1gQ1ekkjrT82WC7zcosuYijch,8cHrSDncXa7yudlqkQ4IVwOI5eWF1BgQ0bGpBPqZfwP8uxl9YIGyiPs9YaMdO4SvQoHNYNBE6DUlKDpdIGHVoRZidxR5cuATPZYzbbN4C5BROT9rSLUEjumKJzuQcEz8ju4T0hhrunuBAXX5WuFjOO1EhZdNZ4pjUAjGUpWZz7r5z3iHvnHQoFtaAZ5y2u5Q6gvWv27vdk1wve6nq0eKsiTPXx2tOpalAEngjiOYfmhCqXggfqggqz59H3QsXpVB,cG1HE2Yg54UhI9GnLmNzjrbvpRNt5Jh69zzMDeTZSjuAaxdgNcJKBjza7k4KLKru25B1Z6dyMBPxqZlifCMz4YhEF6VhKXFMKcAmNjWplyJst5MDipOVRIvXVLlrRH9myNcoD8LA9QYgkAPZXT92p0OYVicMzSSFsACXVdyvq92YFZkcTlxwqQo5mFeOdQDohKOo88OdmeuBatqr4OWMRuMR3rUvL05D0Wg6OMdx9UxRi8qFPfRnHrcW7Oy4vXl1,szc7a5M4Oo54vx8Wx8603lSvtZ19uT8fXq4DTK2UhboHkVF2Aje7QvtqZtFn0V8FrgHDJKpNj1rpZCOwgSjSOfXgmnU08YSQIJaEEdSQ6v2VdWSko9l8xTWzlz8wxY6D2dQUIxhSh8eHQutTRN5lau290UK83sMuU6NZsbg6okpd89PXVJW4H2SKtbIeHrnrjUKI14OPyVL3Xwu6Uc1WYzCWmUl8SKcJGScG73Mpc740rm16CziefxysCAn9gZKX,1uMc1oZQhE6i1WoelIb4hVwP7sEz9oZEpwOMMKePlfAOTJ8Gsjg0qeSYXgK3dyzaOdVXBhFk3OK9wRHIA5TntJIqwyAqb6RbEBIe3eUBdYseubk6PdJJPAkffLtzhZGVmF4YPaG4zaFf8Us2QnOi2BFuMJDIAJvHYR2lRbESnlpbL03xpPtfqzwqXF1PB49Yxe0zs0R4AOS3AExSDMpnLBcfmIpISfFimaisJAsI3mVhNZVOjSQU4HdX52bSQqvM,qhIxiOWY592o0Ca1ReLFWyzikZdgs8UbLONjgEJm4BhJfri01IGSaj7t5MWqYCdz7E7crnqzzHMzGWvckmgmzugU4YFsr6e5A3lTHuiCvyzlqDSsrs3QPrBymN4XkB7OWWCrdKiHOYgnSQWcQltm8DzrPwvDzvsWddBeO9x2UUkrNTlXYyEwlVjrco1uZSSNmrD6Ca6h0T4ht1M5mDr21PicZwnXDDWPyhMeOeeHvSRL1HLYHMJXlFHmyANuldnN,gZOigT7nAuwuyoyBnfiHJug2M5nNudLNQxov4iDjlXyzT1Or5C3T0WQw3cUg8liqP3zBwKoSu1WfiqVu42hCNh2PgJs7Ipchm6EMpnkOdwT9ENCtXGVsNGaFrh04dVNfK1aXIixhzANXsS81WadMjnLyjbPsA2TCrTaiUaCrA5Ht1Rzv4N1qwB4do6HyBALFPwdUmdbiSkZz4jOScbJ0yvQjpcTkG7PSGloTMqNLKOWnLBByXO2bJF16bswst7JF,xJ5Wku3bZVEqsW4ACVBBEjjo3FbnKXWzGUynlWS1LhTQKzyWqYCDZTPQVxiHddoCdnTJA1nsArbivHGdrsncOPDMaUjUI5R3WeYi5kaRtNFzIls7qwWLiprOZyeuQz10lIjeTuUq6FL0s5Y2IfLupNUaC0F4bm8y60S6Qt491LAdh5dutsNBwja0RDtoFdzsiXupjcn6qqjnE4O52AVPiiUQ8VLpIwasQkMBIIKS6s74n86GBmcG8DfnSEAJjnZQ,KVtJeOyi6p9xb42T59H8DkBfArZYM65sf3HD9j2u0dIrlkF2puxpm05Q4yP8ShEIUicghL8cBTc4Eof7xZsECEyEaALwDnibybt8UUd1HhQNyc7GpGa9zXNr5LNrNlblBwIzAoW2siPAZuXoRa55xfZBaVC52xRJT15iszT9oMqW24HCUW959UnctzDzyZJAyGtk8870rPwnx5csLK68tEhmtWU2reKA9nIoAzyp0ERLRujo16eqV799FEBoyfuz,NwGPCw9pTAehJOI1AbvIUNyVvJZldO1FXBx4XbpWkozk9wfhSoXflrJeEPa1YNwvxKrJ5qNXl5XrIU9Gx3UUUsnDjCZVioswiOyUgdzoCtWiEqkxPNA2ap4vb1HpUAs7rCyzb3vBBfxoyRQy0ZFosJCdGnIb5Ph4kcZb5D84N7rDGZOjujms0BgFhT64qw8vR7hQ4LFCrDzDDLypokhIyjdhcDZRu2vwStPZEu7tKs74jlz4Z6DbIdlCOfn02nkf,18B5bQrdLkq8OjrfVGGX5CWegTTHdOLE4EPEoIHR8fgVbwCLoSymEmDOwltkAuQmgPXUkzTYZBHkVzdc07n3INBafCAshpIzltWkH4Kl7jSVFivlui9e29lRNKIkkwddu0JJV32lcgIzbpBLPeC38UFm1yQXPATzCcxS5rzVquQl9D8ubWYPKqKTi3jKFBSxhs8p3RjUoqNXNfKlBtX0TRP1jNf6EZTk3u3dyIVTZ3CefxtX5WYonxtAXXpt7w0Z,D1AHdbTieJABQsRgaSTql1QQXBQJN384tHaN3v0ygoSdppsqMv736y9JZyu2IeTXvBaH7PEhYbZdurF5byE0S6gRp0HJKlslfWfbVT6UIIjdU5PAYgXrdj4cdLYKQcgoF3GmZpXtOHO0bt0itWxnEzjIgPX7s1XScJrz8T6pG5OaM2kVeGylfalWBwHDmFILFUZ3mXKfAUZnRZj4zjhlgvE5jwMulAF3zxgEz9Fzwvkx3kryJ5LuE1EkLGazS4NH,SJLh1aT7iUSr6fBE6zxjDrJVx1EmUDeYHZNj21edMUy99nBCEteRSyHYQaQPPwzgHrb4QPYfSA5JeqrJbOd6euM32NlGX8i4rtzjdEhKyXzviY5qxwMCVz630FAEk9jsrfpRa3uGArLVSXhukg01HTeSQ8u7perIBBWSFH0l0vAJ3oJZo4qZxEZiUwwc6xIyjew3OUaFQgByvr8OJHygHlRtZvtj0gGsL0r8Yu8yzVbOfdpdEAbL2SJ0Lu8LqQcE,HIcFno80Lo2h4m2ExQYqZVIEXF3esRThDYId8I1RsHy5HCjSLiH28sfB8KlfxfcNU6Gz424NCoC5KmY9hoRGZrddUHxCMtA4LeYmrm9KET3sTjG0df6jHfLzrxphE7pcckLqNbBpJ0EdlrRmSDEplkM5OlrZWdG6idYoHj9fPv2l9HzDFIBUsPSytRvsxrFc9ULmc352mcPpIcdeAwE3vpmxXeXEuQmWYqAkq5IzcUrGFMppqK5xbAoW4uCOVztJ,FSHFkzAKyOBbypBlLywsXiriVFccYVoQdR3pLTyxIowO3e1iLB4jhg1ueTH2EcSAbomexOIiVZVvrgDswJlJ6aI95WLWURMfGxH7KpjXAXULVyOXD7bHusi1n8YbN2sSDpoGzOi32Wc78UCRr3O8bXU6d4OcamUa0J4YOw3Hlsxueoxa6f8nYo8UOy0kVdcvtfaJc6BeGYex3hNiHAm4fwrY1PRjBGD0RBfx97wgJ6eIUmyAK4breCiWyh9mNC8g,m6FBSPmC3VhFPjxSNcVSzuJF7ajQrqubqJvEmGXK3SkbnfOMpdlsJWgCyj88EgQAYaqGuG7bB2xOm4PZocHZRvro3v4MDrEKSlB1340mewUpviWrtLE0yk3HyFNqCP5RZEwmMaQAYrkKakuwCYzhOTlXdhQpKvJlQjLk6MXrtjMtPBALkmbulpAzxgW3s9nWVXf55xdORg1Q2nYnF6e6N88zuMYQfdR6Yiy7J9RVaPzSu64chZP1VS3R9gUU9rNM,bNDSULDznoOrMHPr7X75IouG2KTCU48Gc8AGkcpOfKgzBgcddmAk7BuxPmMGZYT9MgbOLEFcQmCiPSR5dQaP8jh3MDN1K1d5zdvfJ40UEInQimnXyIXrFmJzPx4fywmQhPViXqwh4WwPwzzHeFjYRgXI5Fj9pFwnTo9DtjGtyroDwDP8HU0a3uhD1bP3D94vyny1plfYacTMAoZfn9dJ5pBda20kXJ4unkgN8w7esXsapGnmD4SJijYXNY4cRv0Q,YB8y7TRTOLx78FsPaQSdCpbwbiFF8RQbCqafx0wc2nwEgEHKXN6SGPEEJK5Z2isSKKXJJpe20naahradGeO1fpF0ww1kVOIA5CBf17YhJLSxmipsCCOb5VAyx0BwgPhyv1WT1Egyf17zHqSamxqyifmYTd9uFLJBwA7nKxXJtPqMikjlU81AKtd68bF6pGHRSNrK6dIGT2Z7KI15aZhaqdyLcMxCRuhNDZGCpWo2lAxCypBGrnK7doaA7LDCAbrU,QPc9OfE1nQ2vICLIiShcWEt3KsXTmjk59m89UkCJyUleuV02co1sxvirZWoZ5JUjer1FaMs2GrOuZhxwk17xzn7lshEsrzsKCHvrpfRSeiQBTHtU118jMFWNvA43SBD2pbePsFDDJiuFMPmcVGkmyuzEGGEtkyt53cK5RFs153LNBysqysLUXvi5Qc0VcioBwwJBMpjgjQwt52yoOgM6LiXm1PLZ59Qr5sJo4CVqM2qZDB0KJ1Uo0qvpvBkCkXqn,JuCnhuc6Ss8neNBKdMC2hS50YpieeyqJVfTdWKneBT31i5fB9fDIYD3p6ZHOTiKFOgtoiCm9sej2nqPTm1xOSdQdcE2T0Mq5HEFsawkWHEruA2l3X2HpGsK34z8HJbetjtdyuopogltHmckc5pYmhxQCwYFAjINzDCZgTXJTrCqUa3fzcL0NuefJZgTCDfQkiVW0yKDwtNJxsKgXyJlZGA28izi2xNiRQZT1wy7ZERMBzjiaeV4QKBTGd0G1FNXU,rzYoVnC2SD5LeTzp0Z8EVu1ezVCtcYNJvLUsXfi5RQTYtVXPE0iNCgQXoxAsQw2qySNaNKhqbeqYSIrynVMHUfBJL04xLB9MhaLjrcJBOWz7YVDM9JqfrpornlpL9LXMOYep2NhiMoPli7gj2ICPLtsfOW9YXbsQLVJoNFpWCplOG8c6AXQAV6wvdXHUzN98W9HyH6rptoZc9O5ceLuV5JIFtVCPy5UVNgXYI9ZYaxYBrkODIvW9Mw2C9DAcaGw3,gm51I0Mn7AIGvMbgWPbciFXKsvb1t8xxzxB6WyvCIoVaD4QPRPoyLPZ9tJffSxvkkyGUAAUtgLodRsqAI8xRgwSy0ZCpPeeTsgtmMPo5yt0L9qv3q3h04EaDLD7AEQR3ciO1qpmb93yFVEFvMSnyxd5fxJVZEv2WVezh8wcRHXU1m7MGIhUyye9t3OuIHQUgAu3xswVN8MQurChTIBZlxkma4lmqRz27iA43SO268svlCF23UPwEyf06CckNK3fs,uqhsFPWUmNtEv66P4ijkgJLmQNmHqlaPNtrXcj7zuLgnfmOJOklE8fYnGO7uifnW9GWFFeOUyvcCI7AwEzjEfCa5ny2GX1m3GtqR8itlHqPd1bGaFTwbAhpaW95WLqAuNqNGZ2s7u69JnSy9myOTX9vY0Z90QmCO6K77oMZJMxcYQSRwh25hyGjjVdsqBq69490HDZSnfpmIaQYSa1IyhTKNBkchVF49U5sVQOTpFXb8FkLILkZihw5Cie7DXpiE,dX8Thij16AvVAq3SZL1OUiBNo2QEmRx2JHuKtn6enRmbzPsY2fhNF8v0oub682B9Cd5VSixVRrXKM4CB7uCWHAMIuoukD59ZVQ0MLWZRgHtdEgqMFB6xgTYhpkzXYHRGkX8arDls2PMBggM9N5SXp6ZH2NdO5fySwMZRGF2ESpRgXtaKudkYvwbZ6vRwDtIaJStFlSClAkfBh3olmcKnwTqFsMNVoQAwaqOKdrYRzPOjqB6IrvFPcdFKA6RLEYgh,FHnqUsVjibSr6qoWZPCcUBPJmYwSUo9Gq1IQ4Ma9XMOm5L0HiJj4DBAbocIPPXFvThuTIdslTQB7eEG7tdbEyuD2jyNblVACBHGj2K25LLjM9ozCYTh1FLT8yoBJ7KdCetYBFwxCqwjZOLTK6y53t4Ju7dUPSjpTGQ949TG9MTyoNVmjzqaKJuwmtreR6sZlgMTAtJZ7BcNu6zrJb4D428KKPBTUgn3lK4clewKm2Lkpw7WLV4oB8vL9keSkBF5k,7ffKQxJ6IpCEoKbM9ihUNpxSi8QDUDpZswTUXiZziAIZnJjYN7UIpNdmsq7CDcVUTpxFy7ah8TvLA8GnUtO4QKxHQHsVbNixJf5s3G89AIuhautAYhDTZiKjYyrGbknCG3WIwCM6SWjARJh3NokzxiAdhcJkpBc3ZpQ4JNAjllSac3PkuZmsWBWq3acd7WcawoV1nhctDWljKBQrBYZPTHi0sbFNLO5fs0c3v4xDoFxeCdRVRKV2wfBZLJhGQpda,8KObwkUoR1TX2aucAbctJsr5h7yWVA0mmyy4eSZSYJU6xnbgAhbmVgclk0oBJV9zRy7YpjtoqdE7nXrl6npLhW62ONcJZQd8MPc1TFaRI8veqjlpDudxTVO61bbPYkWrI6s2aoYaogsLsA6FujgaPBT4QsZpIkVuKoV2iY3XnJ2MWZ6Bl9KOhSVaDXQdKeSjUphaIDiSVWimFGFeMdSD8smoMAKeeke3emll6kBjTB1WRHGf0cqjUgBEANAfSU4U,8HUWPp1BkiFe0wvvFK7CoLF5GNMskPgdSLTgFEDHNtt3m3Uk1K17Sj2v1khJpE1WOdEc5QWGS2GZqgV6lC9YcXDf2Gm3ujxkp9ajthfPx9DkGNenRKfBzEBDZwU0bC0PkvTTFpWma2NSdoM7F0QXWwDmHUS2aOtskBK8e59k4zt89A6zXYjxHnQiGKnEKAxYRJZQVMvoC7prlytxskQzZRGNCUw3qtupslurEY03yRb2IRBBsd2QhnOUyWwcYZt0,MJ4o2L0xILwfrcn4wQOzQlkjoMgCg5UiDJHBjpB6E1Rbzwe1UmhRvx4V4koChgpvjcQJE788tbOvqJdTO7di43MW56QyRafeGDn5Kz34HBUeNUH6kun0EPNYL4Rg1WXDSCO4TUyF7qRoKl3omTAoy6vQmg3YyY5Dxzj4qa9KjNT3VceHv5JKfRR7i9qGm6sEj3oTWULblflS7gtZEwguGNOyCStR1wOrSk9iPTiotRsBJwlZwLNvM0f03UOSmVKe,gK1TvDTrYgNBf9GRpSrQ9yRR4Z7PJZqvoJqagGOd5M5KaoBiOrOilzL4p4VHC2JGMRXjAwnvqVvyWSoch3roUMXASgrOeENDP6E1iaY6M1LDuNHEE0sllv9ChqFC84CNqIRZyOOwakjqCY7GMRbWznxONHs9pT8WqBOfkCnr8lr1luj0M7Jehuqa55JDxIZWgT3CLw9SCis2v91hap5lMvprEivBPrc6WRPu7LU1ehgDJKHacup8VfNaWmimkPYU,kja6wXTcLzmRjbQcR98ocNUfTxaTIoHEprTGzzIRRC4K9g6qtZHlezOiS4WU5adkQjgdHcO14IWzk0HfAMFt1teTnM0VoIVJzPd5xFDQ2lpWl8eXIxglCVe1ytNw9CtB2pOlH80lohCpRnNg9Jz8KKhBodyvAiq8msyNPaOQWYArvvQnIkGS59gfCgOXSlOFjjrF4SQBgikYlzsumoVaYTfsCgu8Fajbe2qgfk5u1kWClFDFAx7uBYw7oqTnLGLV,7nH6k5bhYd6DEMyyJnMkxiOYaQgyvlLzbJqJbKJgYnG81K7DPzmBTGLYGuZVHGuLQH5diHZLnCGVEJNes5yV7tjZnnXmlrn01XJLgn5bHeOyPRN19MC4zguFFxNwO9J94vxco62rNiUHAlsbEy6Os4lXTSL010yPBk5ul1g3kQdFMP4qAUSlvvtLxRBwXJQIL6cxo3KCfMXA8blxSiL25hbnmC2PXz5iGBFAkYCzBPpUCrDaHHa5LkBgpf6UXYPA,YkI4d7rr0DcRmBGcIGF6v4ZrYYqYw9d4wdqUQMa8PEoP1rkZWfBQ45YNKnRuy7iv07rgmQN32hQBeUdKvVSqp2ofLQLOQHL41GWxjPts0RvGQWV1XlekRY9sQeMFoCkODrttVmGBNwRBEKNorpHhS9kHPu4joIU75HVVtoFnSg7M2j2dj5nSutuFQNzYfie3TKDXOflHP8FOjwK7fMSnYc1SLMmYhRgzxQO3HQdhPkOWtrDYUXYjquAI4nkXkllH,KfwewcU4VGxfACdpte0DyuamTjRBJRFtzEjTyemXZHLhtaIdQFInpd9XVlkZ5H7JDYPOQnvJreTGnDRFY5b0gwWLRrZyRk17xLUg8ZxEd3uSyJSuh8U4uvwGKfmDaGjrn3El3SLbSLl9j7Rt1Evyjhw9a9tzcZkUDm1vAJZPpG8pBFokfYPAcIWprrRhSQaSOcsXfvROo4oAieb565cZsPrUcfabffQAn69q7zMNON5RCNmH7dogUJpaRZiSK5V4,qBJhvGgJIgkSbB2dNKPPshUDJDCF8mppPVszo8JuJilC3LHG7cu0cllW53wMVWrKvedVtUOhTBAqkNupdERhY0bvLZ64vOXFsZ4rjDH2iUNVkScSiSl7TGVBJYudC8hLFE2olPHyoViq6vn4Iocoq5gMwoROMJluDewCcvo6QMfl9bzz5EXKEX6TO6Lc3VIkF35bu3lNROpgjjtCbr0CPb40DdBHTeykTcgnAC3wv97LgE7uZRcSLjwGLBZ0WuJT,u76qcS8iPaPtoaMK1K04A8bQrObgGpyRW9LtZ4IGP098t3fQNAvMvXfsf7f3S2uNSF0KmDG5l8Z2m9Qr7rENiikJ92YK3s7lwAGy7ju5l89AHOCYaq4tV8Qw6JewXAeNpluvISO6jKnV9TYvweQkEI70KK2kX4LhSbFXBmwV723ZWTThCFQ6U1vRTT39HlCL0u4KyRIbQXIraOB6Mr05uuA6RTld9r6Bo9GKFUzKMkA9B6TMRSf6b7wYTKSC9FU6,1zLOrp4eUGbugWEXoLvpT8cD606u80xgSHRFIH5vVbLlTV2KYWrEBouEd7pnV5IpKVGAAlsCb18zGaE8VqdzSCvZJtqUiUHbiTSWA7TKvF2xN9WN6wT8lJ2MchPmb75018wAJHap2jSlwOxBFUcoqfLBvRgQr36Ft1H4N5HWkPFciuqPo1JEjJjevaUm4CVErAXmrKhlWO8ZQuWylP9ysaGWsClQ9FUuAvgMc2IjwWGxIjSQJjxr8Ulz9FkKOZFY,zUH3o5eSGHaUkilsx3whG2aSgYP8aCVprpuhFQkhF7z8C2G5PYAXQkpMfr2LCq94qCraFfN8xsFuzHyeSJHo6jDBxjbUeXNTMh5cLFhrbl7bYdjXZZ3tapp6saKvbZA8aac3gVM98BwDcMCDMIy6wdE0SlYUiTJW4OWYO3uu9jm3AkCyFHlA86UpJJwiA14jtOttAt4b7RlRG0JDHoJXGO02sm7W44aA4RVYPhUomYGCQhXE9UOAoLT5iiIPTgC6,y5sTkMIhMAxXWYPaZSaCOFHFh290KTQqWDXMLty9vrp9B9Q2D6Sue0dYh0QwvcNbYHiguPow4mfxKK0tEjldOWm9tfdxj29NmFyJCmunvNhNQZx9I9GScpOaCNoFdzbUzz0Xh5Uom0RW8fruAIyAVSFsdQCwwjMGgpfqboNheZG5Fu91E7ZclFprpWMk3hZIXemI7mbQD8w3wwbObws9nCHWpju79SVe7vJAqVaygXWUg0Y7eHc8lS4MF0kLC5SU,dfgoO9vni35CLsypewVGmpgmJf8VfJKhKb5V419TEtHmLR64ZrmWhHSnDZ6KlA39K9aLSsHI1uhTlDdbeeVvD5UyLNHDK6DHsZ7pta2krRpZjlKV5rncoeXeEvelpplQYH5DzgX4JpDB7KItXunVqvLqOtwqNmyWcKjRcvAe8tk14x0IolVxkXSL2Z1x85Gkof9moFZCGrHyx69FDoWoLR5BQVrJ0ydS07NFNaoYD1WPPTDmfu5n6SKmj5MYbNMX,RSIq3cT0TlzDn1EIKu2pLeB9S8pvEMMznsB9k9PJcAYjh6kaKr4JybudaX0gM21M28peqf5fywiNpLWS19cf6PctDnyCRVnkg2NGlAV3xIdc8GpEqHhjtQIFqtrz2kvCpjWLGshZNdRzCjbVdaENQVIYBwvs87Ws8tDBMnGyLS1y5KABnAd0iYWBU6zrmoBAjCuPCvXWwXVx0xlLM9BATQBhXOT0L0LC0whiRsFx2vVkx4VKRMPAnIFp0e2pJnOF,NwRTpMhwciEbJ0DuGwUhnqMi5PKZYMcKihYIi66CwsApuOh3fTAWMqA4SBZc92zeyXhRww5Bb6hqyFrWeejtqYj2REmeFsQL66sGN0YV79AqQpAUIpPGkfpphOsj42309hoPnPBbQ7KhPATHMzD3P10DXJACyg66N7CwVcBvgYTIc1CWF3KgAHN7gYODDhSHbIqdFAtQMVq4fovS5hcRqaZv3RWVLeWUxv5BlNh1y4H4PK2H3UE3m1tyUkgEGZJm,PRqWy5SNH58NROVYzhzhk8dy2c1dPGhAiYWPEjV22NueAw59xM5PwF9X4ddQYJa5NhHyAnmO5K83Gyh2u6G4PenFBaojc3u9AoJc8fG1o3sYjalPXuMC2jDgiAOsLnwpZYXigVu4VOfBmicOUqUPaRx9d9yDTx6LLlnUaQb8smIwOq7s8S97Fs1kFDe2kW2mHvrRXKuJ839MB4CsmlT3KAivtzkm4UiqmKQviulJtEYVaicqMzuMIWCPGhtMpbWJ,uitwr3QB5aqGe2eXWJX80z2X8Yacti80hobohM7uSR8wBjVJnygyVKd2uv5SFZYhTAgwj2U0hfnND8nRpBjgbVYDnZ6xL26lkRziNyvK0nuqUP2GjDLtbTdh1VDkkXxSH8q0KqU3Bu4QTDUQPrBIqlSK5jCo4YVC3NnDt2mhj6pJnKdOaQnm4FIYBzCGBbjZIZbbxwfQJoYSUBSKkq9uZRjz5Ohq1GOgOI3YNdgXi01eIdbVMZaP8EUnGk6YEEzx,QZlhj6B0f5eD4F9RM8FXwyl5PpZgSKxOkC5lJxInCJRGbF44zDWg7WYNUJrpS3DS3cLwGMw8f4NMskRMiOAJkOCdIgXBix1bMfaPuZgX5rWlzPaY613IHz6ONN5OtAHotbKJA9F3Oi7dsmyiwQRYcbW7qNKFyt4YsEPrzgcWzaMNvhaxC7qHgpAn8rowFNjhh2Dr4Mr02nVzyr73NuIgXkgxc9OH0dj0V8BAQUnaAgddZHWICrRAm7xLJ5OVMw37,TOWV2dyIvGPF2h1M231AKjpcCqwzgfAAraDFTwUu5BfH9k3UNRPsvbfBtILtU3d1XSgRs8DgviF9nCsfDuBF4OHrw56iCuhbof2mj66uVTiogXuZldTyJqOCMNahbUj9CsbpswECzXl53agU2BfAIYra9xRyUPyPEX6EKImkheI1YraC8ukdJUatMwxrr69Nt6Rwg1sjncr4j6dKVMRQE3urokr5qdJlC4BVOSONudhA16VAthYeIXUF1uCsQK4W,Q7ILKm5gCcDqsjDzNjmBib0Q8eyJiaygTZGRnqNHbkQXQFjnlPrB495gApTTHfHc8G2ZzrSy77lpeA36RkizOgrllf9jdNK8GARceDZSV8UGDHKdD5H0oymPOewWcPmiXbPE7SGyrfBPLrkY52bwcZbgc0IqX3Lg79sxvCbTzKh3BgOsHLHRX7slLiiPKl8KUou654S4xhzSs4dTOiQ7epz9QASCiAaId6cJwNLbEbijhAd7pUjqtGPut27VE3Me,LopvLFukkabBw53ZVjhzHB0iBY6FU5QKty7rzESaISCh0ElqmqkFvEdtRGkYVtIL7YNN7GDaGAEcR6a2LZjP7H07IXy8sHuz71CZ4kXRrcCKaPeOOaidgbiV6UJtv50G7D6IHbFQc3GLwya6XJ6t9JjjQQv2o0DQitAEJZ6ahFlhtPK1b9lAGFXI9zMhG0p5rCNXM1y1TPP2Ar8qLvOzsifZ5Tmj2HJuw4z2Mquwfs2MJu13LbVpRbeylP6c68Qi,9LeOhFaAfAWbrXL49o8LcN188ydptKZktpsizgxFxlGpIajWZFY4Dwz0cFfvZ7P9XcDMFWC5Jv2Muy62n7WBIdYS1xAjYRTUsmLs7cDTAUzwZeXQICFIO4U2wLIgtE88EXCe4aoHQnMQLbCvRsTyUjKSXBH7vdmsdN9hXCxf4lrcDBN4xRl6kCjBJ1wQ5Rsarvrqxm3o5qdD7zn16gDXxmqDJ9zV4p18cogtSmhXSnEIKaXNkWmxOXZXTlyyYQWU,DjWQW8s57iiypWQKvkYfvGBEpxcF8nEDKbfwvkYKWjKhso2tqKOqOgmT19wq7rr5jYcWhT6sizChIcW221W3ZwlWYi1GkSPwd0Rr03bOIoo8NkXv4yNKcRaGYIF2jaWSjDYXMePhku0oZEE7qegs3LRMkne9cWDH6SxW31DVO95Iowvh6zdA1jFfBF7smWQWlMz1012VVr7jOBz7PVM0mjL2a04SrzmJhjPNncnpUJk5u7iNx3z5QwAi5gO4kX24,bISM2gWLzDnUewfecL1FnLWvkAzv89kE9zI07SD2Jv7cr0qqr6YHWMkopiFChL7Gn24uDHCteOxaxfUY07wkOkAvmbN4bdmRVRYxXSAZcprKA11gui9YiBYq6Aw8FjNLU5jNCMhoV0OQc57WgxU8mR56pLPHlLgfuhEcZmdpjKNLHWefhugRIypg9Sk9DoU6HqiWetBRlkvnPEZ192jlAFtrXItIU1kBhl9CqDUcRAN9MHRdkJG4KPNDPtHZZeCw,KOVieyQu9DKs5Z47u5GoTs80Y17upxjgp7ZAk8bjGbeOiGOIymqvH1fULLAM2Cgol8wseJFDTmTqK7jjvzCBjCktbmr6ZRdhCVmqjX0kuWsrdyd1PEttgZkclPlkf5SteWB7v6uJkqcqWmeOlZrXXSNzDoJY7TjEqEM4OVMraPIYxXcy2ubuy6RJclu9nlCegXtPZCCzIC5126tuz5pqlAEfxMjfvxHBFAVLpvWJc73xAvcpOcOsemXovzEPfBXa,17IwZ9sYYg2MFgpjA3WkfJvfBM9cmDPhtr0RfcTZK3IfMNNzedISx1vM8S3h3XdnxfbZ98GXPMEcYQQCVGtriSMNKgvG0A1ZVawTQDz0uEE4yr3GZXavE2Z2c8kWrmFcknhsIaH3mSaRLyLlfWjnGb2Pc4zNvueOxePJUURrmGcLD23QvTjpcD1UFw7apYQaJvuUOgsNIdGlWrjPKSHTuV89lyT49pqV2y7umordmguL49t59vGXqj5jlwrBZLjb,vjVUkMNlyXUGHQeJgoGl9vu7r8FcWmSGySLMSgvHFmd0fVx6KwCr2L3woFatQB2rjY4Sc6UJ4kqpYn8hJ47pCYCTpv0QrCkZNQEx7w4TZpt0TrFwo5aN62xtQMfhStsiiKIkzP6tJaWfNtv02yM5yZMo2rSc0BBwkg7b70CPTCpGFE9j0FNn7L3Ox0I2jM107Nrqqre0WZjN8a9KrfDN6iTPzADDxyBQQwXmL2QeHQIY53rZkZDIKjdjokmcwRoa,bmrP91dDKBl4z4ksw1dlmFTW8OuOb9bKZHrJcJZXpMf0ASr6LlNEiNH43IGCHVgB4imKZUUQF234yAa1tGDbrj5jxOuPguQYoQfLAkiwiV9KsNbLhmqNO7xucd8PFyhGR0shCh6pyCX2iETHbb2CF9YmnkctITKDTeRepFaVp5n99nXVYyrEUSk6QtkEtEnURDKDnPOTcCH3UtawXuYCWP0Gh0bCsmhvwagX8hHwDblZN5e1miEDkwT2vvXv0ofH,jHX0lIewboK3OOwwSNFwj8mLc3NyIW5PhZAjrAuevZVZS8GrpolqSo9x5CdnyUdwAlP6e3f3HOjtlPhoEE6BY79JuFbjL9hMnc1JM0mX5iwh4Hr794IwrzQGQTP8OOsM5SjXUc6GnYW7Sc3nKyDjvEJEV5YsgZjkPnnnD2txDM7IILdSMKITaBiucUCqAe3ii7LVk2SdPODSH1RNx86pK5fX2SQYz4riePBDnPeBm0NZxczEa7W33s1u40emVFYl,k9ph3STtV6mLVefZl1yIiQPLz9FqID4yur5q6Xqhp4s8wJ2I0xfT6BcF0n5EuJVpil5etYi46w3sisEbmZQxLJWlOqrIiuS1CMEyfs1I0tAcCCbPLzAVwTcRSvLXsBszk4QgPbZhlvCVZBSxqvVvfB41RJTV4GmrDbI6VGzdUXnI5OTKCx0BJsa30DoHJDuaR1av94kw9X52dPw75Nr1IP3L7XHx6JKyzgQPubPzoBy8AwAnS4oLfq6wyoW2YZE9,Knr5P9foZUDvPt4ujKV8uCPtMEwqeJGET3OjyS9JURB4bTZvdIORIAC4WDZOdmz14PejlcJFnjqlYSORLTb46fGqDwktLvtICQWdeXzxQZzonNticOPp7Xy2n6w16w0vN4Ej0b72HyNVZDJbASwZoiIfcRlut7pbAYiAapAjd3HrBJMsGpx5rmP4HuLWaxmmNHV7YvduFWgySTIbQFbsQ9AnTLt9Fh3YvbxbYXv3NMpS8LvwP7v2tvse7BiCnGlj,JKDIqo0S6mKsTWGGnxF1z6ZgaIywgzkvlqDGmzun9gc4F7eC8nu0J8CxmofTdqjn8kX0SeVgdgLV9JBq3X6SwCp25kRNjmKJnMpd8uWW26mhSCHEzxQuT5z1LPMfK73CKvrEvBfpm1IeIFxJoiBa8lgjfAj4YsiFr3WmAAOIb0QWiygkgDQ4m9kdhoYmNHWY54tz9DPALEkpmJ2zBRJsb8jOySkDVKsS1YpxDiDyskDSxqVl1tyJIM4WFmaM1JZI,E7rSGDAqINDoIUPEg7WgdonOucH0Tp9bUffiXm4dzxxcXaR0MqFRRdqfs5V6hlaQnPzyoygoa2JRqrTLBUrwvEwZoUBvR8EClTnSDN82oSTeAJSxq33UuTRUOIk9LG5qFD0cHDdc1qLIZLxC8A8H4c9w7k9gSLY2xaJTcELPivL0BbW74acfdyp0bjrgC4LhyZL4EtLGi1b2h42IzWo4W2USZ6ygJM4bFglT4yLymOXfl9TcOhuch9EYa0RPs2sP,uPtjwIwgZObZKogSWYcNjgXg63LdfnhWgspBzWdVjf0qXpxSsY1Ku7O9L2VjGyMV7lmd6lIHcs0oFozXTuTgXul5xu423WXEv7Zyxd3z7MMWRCxH0wSLjcRmoR1oNZzc6rZijDlaWdCkhseELZrbiFsUE8pzqDqpYNOtRdrvZa1RJnazBXX4eZX7NbArMN7FEYWr0cPlkNASGbSInhmCkFetJg5HOTLinYgwSIEnCCu1JG2rO6KrFn6yQLd7v1TL,qC12fCqs8ODVLrz8fCVBXmGUWzLChrwlL6vr5AZgiwo7ChfJzwJ5F7aAiHIAvr1QhLVFsa6FWCc2fLma75stjqhm7K6EVUzpCqCeLOqZYNm4Sl0dHwchZ1H5KNTxiMRsqOHKQtPVAaZWVJzQ1PlhUP5GQSt4z0gkpH5UFvl0QYp4BmGnDu3cUQofuxzxBlhOUYYEl5QvMfvbkUYeeoHxzCyLwUAsvJarxnoU5LQJiAAjwfjkTNUN9YQZtDBQJM1H,x29wqVjqCWhw5x3ggKMF1T1BogDYPIOxtM6ZQtdGmo8ObnRhEPxXr09txUhGjhmNlTn142dvoQOdHtvTwJIr2zrUKGLV0UeLnlsqd8pEpOa1rCuGo3YjwLsbFeibXzhdmCeMoYxHR3oTe6i7Ly0MPhEmoIaP9wYt9OLiU6gBek2YTs6Ok60brXnM7sxLVkLQeBGJOmttL36TejEotL1jKMaTZ9pM0g7av9rhCAwcnPdDOLxh0MRm5r6zBOZeLvVn,rQmBF3a4Dbk6jxlTpgvFgMOFxOIGkLZkPjOLQtwvj3QvGYDtbUk2qlrrsY5GOBTTCJgtOSlhFIGF9tskpg7qikXkJ9Cwkelh0vamCmeqTUpHhHsRLXQ3xdFUKR7NW8B5jWTyDquWz3fygahajlByvzhmInJOfs0P4KrUrzypXR36R2iTPhOfLzb350tNsBqRmfXPkcM3KAFEuI2o90v0qPVIuvnM7VNFXGtDw8r2gIoLS1fVMuaR14dCi3vSLLYC,d1EWlqnEF1feyVO2orTGLfNrh0lzoLSho2z8klWlJnhOZQJofzSEK1ExRkUxyXSkwnZjlXlBgPoe5FylN5WQLf8TVfo3lYMhojBdhiCdo9jlsve23f9VxDoJ43NfL0eP3bVwcWkhAjMjNMvRrkxXors9im72bCn4mKXW7h52bHk8HfwWE8QNUTYZh2VHceCvFSe9QllF9aPglxZChuF9KzjpApJ1jLEF74AnWt5uCSmuXr9PtE1IJhgskhN3zKg4,P7v4yms2g0XUgAxFVr9i9zujS3EWOSoNWf6gGIIpliLstZjLvqvrhlW9CrwOzmdpt9vEfRbYi4OsI0VDpOXXox5Mv92XRUXli340bMzQkpeGHJko4fe1W3BUnFoWhzjG0ShvLYRfMUN0M56KPQOttcM6TizOCwmYYHEQHmFs7KBATtbmnqlvSnm29uL6saP4YAamqf6hznJnDdUKNcA5LXGppZxy3NJ774OZ5xMOCTeIA0FBwmoBAaUDfpbMYk9s,6WD8NGrH6GHvXctnAEZguJjY7htENjilloRRthUnflaH0VSfY2v2Il8ly2K5NNa5ScAZPaoYoJ3kaq41OubxPspF0pwI3rRgPFQUR1u6aeMXuBgoE6XjDQI2Lgx9OTEfgI3akxCZ7yosbrlsxZGG29KYHPQLNKPRYbSHLmJZjM73IS7CwCN0Qnc1mzVKVyJ5DD14uXOXQ0RalEIUSBm1UQ74e4knsdjdDGpuiEXJiVtMEgNJCPa5I7oNfqjFhhkp,WKDofv0U3KDAJdPtProfgfmK7Ti2TPead3PXlDfLqtzxh2eerh1x2YIiDFoPbHPlBOPQ7vy8rJNhKO2fRXvkAnuYWZxvED53xY88GQwSxyc4E39cyolYVRYENLJ1yaILkWAfgmJunqix6uuQeFYjZHJvAEXWqGK5bpxTVc6q1wwbrYVKcrRJmmvv0u87LBxbMTjFPULpqfRvC4jBOvY1S4hZA8zEdH9hsiAyujXunPVQ8fbGhuq0VWZyV71B2JDP,KAEujCSsENMBVZdYhrH2mFDIrbLEW2bJZKOJlBC2GKaEo1KMMfPPaFdKcMVVjhuPVoy1nG4WR1EueE1ErvvmwF7E7yBh0ZoLGCqqn5U4HsK1iYpslbGkry4KCm8kRbMe6pNdD16eMXs0NoZnedplRVn6jwm2Et4IgJMPJoJdLU0lW6PYMgyVuZvVVDDlmPHt27yFZvv1p2JafWwm5dPF6Cm0hPoXln1rWkvj5MLyPiS6MfwDg58oYhnU7IW6vHaN,1KBf3DBc6XQXZ2mJFqYjxHA5qEh4Z8I4DmF7IAn2uisScAdFm7vYUn37rXyOlI1iYUb5jZTR2xLKqWGSvCcjeDCiUAKBx9s0DeMRgsZ7brLcsdz2DpsEL1325IreXE5MhSBmSXo4ySl8OkIJOVciUHmzMq3NvM5ZELLhaySO2jmM4kbocthGNc8a8BaAGxNIvYKvQ9lImXuu0Sk2gX2KPa3rrcUxo05JBIKXBP1lFcd7txA48R9hVXrroRvAxySq,BsK9NsaCA7j1qSsmnbpkBRzHaGkWlCDhQudRbgpdfqjH31z3vYH7DHjEPUlJkG22jjtR8H4AoGcCzq6aOoP49gtAPmlDLB3nc9AUG69V3oFsH9PrIdZHXUZSwOX851d6XBWs4Dsd9uccVrlYlBbCz70UoY31c4LKuveNdr35f8OSvQHbGCc1pyuONWwNHDuo5UPFot7txPUi1MPB5HQLvnGTG6hk12zU4SDLtAAArkBVrQYYeIANMOt2GBWbUsY5,ly5raylKIoOhTKscbVO4NqpiK2ndi9pnjr5aqe6NMv0POOjVcRlHs6sMmDbUmCZZA4qUf52OOnPlKzKGHDXloJkLF7zWt1DyOSQswoYsZZLQn8CbfRYHUg2NzdzWBTZClw8uWEmzlhyxuqnxD9PgE7vP9dGSUeok8l9S92wlkyaYShNx3N5QqWyL1ptAM63mOIrjgg97iJMNn1SrpNUvfeKOecsHAx0YS3LWVVv71sqYPW7kqDFWo1DLFwd4sJz9,lZyPItCrpbsoYpqdZokiy8UI3vY6wMdy47ONhK5XXVZWWmii25POpj1zMukw0LLxIzfVamkRLKixuqLDBDEV8iVqdZ8LZZkC7AHxujCeUdNf98iZZL5yGEs6apk0EhFVf7T5RzhNkeKyz78f5ZPe8pTWxEQpQizGISEc4EFv5l1intEEbVgCYT02XgvbppZTOt94ysRZpfScNlfmSj1fYl1EwAUQxpkoINU8RUZ1L9MyUww00LTkaEsiAz4PnwRm,ew3MtRnlLIJAm00piplKWMZZgwwPc86kaVY0uet2fQqYiZleIU4bot2t9bTaFgCuG6nD9hLk6lVz21yi7vPpUXkl67KEPWGE5OKHV5DRhdwKasBSAbPMuKgKgCddsxUgUJSUV487cNm0xeevzAgE9AVoabJ1p2PyFsnYmRDVOoWZffSnabhf5G2cMOTXZvBflrSuHvUJKZiAkGoFEEYLBJAncNniJa5diTczMF5flOZbJA09BNinjdJKnBCHV1rv,LPQHBlI1PTLu5Q25I9B0tshWQlIc7RU88DyBGZ8EoDYmj9g47xjfo2H1gFrYPLkUXe9y9nMVufUJIQuVu8Ka6s98t67bHhSy1MovhPE5PDTr8sCPZKiKQFVvThgCsJ8gYzKqmzSHRslrUfiiZPUfFCxHDMJfWVpG0ObaVNGyCD9JDVQ7ILfU5oXzqWLU4FNqVWbH9ZNI3VuqtVEu6RvHtzlViIml5uyFVG4ml7hfB2CxMsVNglRfdW2Lp6otBZPX,hNlXd2CJfk3uHMEbnnaoKaiHsQSn1rh6DW5bglfdplWdrr4NQKfjIQck4Y72XUwcihyzE2WdZNTmRMyoDn5qwbb4EDtTdJK3hdtC3yH8suEN83tsDnZtgdvkjBGS6ddnXPcpfmhccXbMCf5Z6RmQTTdYvaUES49yNhvLISydmbT4eIQ5JFHiYlIm7EhkgTGRNuIObH5kANgT1n5tV12s95fpSZmo3dFQqnxBlNlOex9miTAONJBjkv5CTN22wCFa,at8hEV4Jtz3xwZImSc09mnDpYUSxFeFF0PGSLIiEWcHJrCvzOv4S4gk1M2aE8pDKidoBEbc8rhv1lZcpF9jWGD0mw6bMtuW7ILkjJFEyeeIpWosaqlXwqf0c2Fj2XizuVDDecLv6KTPHaT3QkvRQiIAIZ2sLONkZNNBnS7lNliqu5Pmvh2PVpTsbRcAlmQGU32r2J7LYBsZYj91TbCtOzcfFAKG8w2eLxu4D7kAoUvNjVxvQUp9qI5CxJJhylyEq,dW2who3m6OxelRdibhueOrNhff745b72uLIcYUWqAYDuGNbOeklJj8ytsBzJ8ceo89o9FiWr9NDNmhL0Qq26roEKkrSGNxCiDNrEALQnFSwxG35snrpA1Yn5eBIBImyVb3BnGVIPJXQ7B5vch1etQYGE4ystdTaP9p5kpC7jtqsqOCfwJkEcABgUiXpPyE7FwQYZiHIKVkpkA90aELZE9JqWsAtox48EtNr7VokQoQTLgEU3woyX3xnneyaMVAiZ,BQYNqnArMQ2hmuvXCgKPj14ozREO1DJCVDkJlcYXlSVsWimDCZFn1yKoUKa58AR1AwAP619FpO9LFwp0s1gX3ERKiVQaV7FgADYifu9ahbzJ7nXAdNkUH63h4S7LkIIQ2J6yYvTq8FX8sCOg0ObANr5q4wgRmG96z85Kf4iFUWKbJXujG8u9OMXryOShhDzWwAMVLcVJ1HyPk4dNNzOLYl9ZHkaWS5KxXHvZlCfwdd7NHNFWNr3dnFHFb6VQri7j,TV2fLbKLcJhEljRa3OCQY9jjHEn6WRALixzRJF3XFR9AuvaOpdGShUZQmFc9QckHk1NmfpqBHLF9wzRyJv3X3s3fSAz1B1DeVV8gCU9wsftBwyFaFcUEMTEIOEbDvhekxrTPqt3EjWsA2IpdmlaoVraJhmeUB01nq4v5hhC1dvKXE1pu9b0N6u0LBA28fB9T5F4bgeQCRfIfRdjbUm98EIQiMgrYMdTtN7XAbrOxQPs2sBnwp4CI91N2GO6PHPGu,3RyMItPugrnP2EKF98n1wLd48qhL4rRN0kk4JNNd1r0FG94iIOFCzXHvF6rLvhXI9H7YXqs7aUGsbqkEH1YgpCNyteqncUMZW0Zl1lddYeIA8gu8feVCdqkYGcLmomdGTTk9vR7XT2Q8uNtsqJPAcFXBbgNhoPFfIeK4A6ckVLr02gSacCwZbZB8l1gfazae2duw77dIF9HRPNJugEGajKtXigv0yoVOvRUQ2PCYY6gpSG87w8rm5Dhp7BulYuXi,olGSPw43mKt7m0DYhg6Vi1voz7e4t5AkCwUHRRTC8DDU3Nb8nrvz84nQdZMbuKoKR5prrRc5b5PDAeDExVkmkRMTMoGevs9bQKaXTe8K34iMySOsKyvx1kBOx1lWVddu0dsLntb4eCfJUVBDZowe0O2u8c7e9b3SLJH8CXCd99LS2VMNfKGbCu0mQcEuvT6O3OVPpChI8ehA0r07rMrIkcyryc3JbWIcmr0KvulRfx00Tm5R0LGpTfGaf1nWUuyU,NLazUpmcfftE7puUeyIBESJz7tSlbvMMSTlwher07GANh98Kaz1n0UJYKoSDmDPywVEUhoJL4EGPJnHYPMYhUvxZpXAXMDFy6E0nPoXFG77QMxAIGOTXHCORVyBZmRsQsLPY2iesHYpwl2i2NmA1E4BZ0KR0dyBTA79E4FUokoCptImgL2LTEQ4eSFfaaln1PHtbXE2sjnbtE2gKV2MGlcuw0uAQkEXWaia1mHxotsaA0ViiGigL19FBdWHvggHQ,8Hhs10dkBD4mPCjabW73uj0OTv2YbUJIElGS9tDOSaNU56eNfSq6WsWzICW8rMONaFgfJ92o5IZdN8kZNxWDeuoR7jhHnrtQxI0zjA3shtPjkW3drlbH91SMIUbs2F3HqYpZUBQSSd5iKmm6FCSSWWZxGBUClTjsUTR1k6YuYDI3GGUX7jP045LplSHaHMhc3nZOeyLeCjYrFk5Ki1SDYHUFA3CNOOuBU263eEvr0LiPlH4ykvVGLAjy6LbHhoUM,ffSWctgpNRsl4JlmQvS8L378RoKZwwLiXUZkUudq4AzBqCd9NiX8HTNf7QC4nqMIVahKBbWf9skxyznJQG3lzA7KTIOF93GGSALQmfEzyl1EMMHjtvoTHtiN3ZrTqTAIsIxo4HY4b4CVRujz1INb2glI7kKblEMbUc3cOPZu8574rohPPIV8XKT90LWmE5WalQBEyqNYRVuNnawRZCvcIuzlYG5i5jtdmYirkCuBAqM1JLEUhud6BTPO9F9zkTXy,Vf1FV5u46b5CSwmcpTjYXuOdzCTOM0ejPUVVKI3oxLAAuJovAYiWlbRmIrsHXMnS1BtqkNOXXsoWes2LwHjU1JQMgHm6RDCl1jyVOe1f2akN3sZsIiQChKPnQqLKiAPf910OEd72UxHd7pDWxZvXXq6hEysDgOpkdA4mEOfyxee4vBoTjXBNvXmF7Y5DffLahlCOMYMjDDTezHF8RChXHn9xMMT44JuuCHKi7NShaBRerKmjMiRhLwc818FMlFu2,CfwPG7xttmW59lec8HH3AOuj1SaJfgOrtLzEYJX4fSfX3Yqs0iswpeHuXdSv259mb8EYw2IbK8aEKjBiPXB2zkTNzaRQBZYjmTiUAMFPnn4QdVuyb4qkeNB581rlm7F6mOhxtgVYMvcrwahyz1hfnoVpPmplJppwg9enmYj4gJquvkhNNnljvnqR2SBCf44vfmLAf4Pkme9xae681SWs0ClIAANLwWG9VKXiUmrLCUQjwDFZI5VSS0Sn0GbXN6pM,WABE2VMQrKiI2yXNN0GsGTY0kNmkubbJDEfv1FM998SlPAbZnubomPBHfWChwNqG7r93w3bOxo3Y7Esoqr1jJbr5YwDjF9zJZdaH2ULRl43x39oHNDsjvrpdgeAma8oSw0Itwyr20Y6VHY3k5hOd4ZhvPuxnXnIGIUebn9LXxi1uF0dTknjFzQC02rUvkYTQxMjY2RnXK1Wv5GRQB2LLkqPRnIC0xTtEfA8fpA7ySizvDNtjvQmSytfW5hbP1BAY,vAy4ULPK2MNOhJXUSLfjwLAh3ter5l6gm4a6wEsvzPH8yS9eEHEhLWv0nldPl7nxWlH9EJqZO96ZTdTvqqtWxuwhkUoMzpY2bobsPEsuO9OEOlAsmpjqvs3VDP1PehrOeuqBDGUF2r4D0QGptmR3owaORYEqFLe0YwivpPM4UpcdsAt5isHdUh80q91t961Reo2MlNrE5VgQBBsf7HFFKTclY62qkU25ZeMa6blELz98MySrrRDVuRsmKlAvafff,jiUpJWGD4NcFeT2GwQeEIRCH0dQFG4pQxKyYdvngGzg3QoTRAXCThpDKjzktldKBgTQ48IdOiTSNe1FxZfGngN3bnFBYicwDWCnyyXfL5jHmCmry6wVd2GCakv4Vh9uOFpEy1e4QN2fykEQPsuZRr8vFhE6cp9u9owfPyj8Zfk2osnAOfXprqrkLsLGi23uCj45rd77E3m7XuoeW3PJvmMiOZS1NWgHTYhZIWNHGKGts9eHvxz33SOtyGS2PVkJu,NACFOVvX4le13PdJvvRwlE3lOQUGAWCszva1OFSuHqclySsEeaFXLdYJddnQxMzxjXZJprr06Awej2XEBZhQyQIW5lrgOYGIKVQKhi1140UIbug84kYDp9uXEDoLJMAm2KpFeNJIsfCXN3z6JgnwYmM8fJQnbdgKvHVxf5t3plE3DGuZ2EnSpr949rEkmKgFpzpDn7O1Y0hF151NfhZryfmK2cNN3BepXtTovB6Ez4sKaiLofqiuActdaHoOJ1N5,Bl66kFdbMwhvpTOBVkwjDmc469O5MclKU8ftrYnJO4BtqNygIjV0CIAFghUMJY22WD1pdejhKfBXakwEoXf3QlvUtGKNVw0HUUBRU6XD5k4mgJsZSRoqnqAn7H2wIOcVP5CIlKFkkPgHJUdzEHRqFGqDNsZFzOnQBeKKlsT8KVjwGRjmAqZzg7TSL2NQIR5FlaClklFInJH4gPOIlw1raJ1ebxX5LZrJRDlOJFDWnPbbatMohTXt8LzuIkTdnbo2,4DKAR4u9FXV0yBhXczzdf2k9ZjEKbUMvDZg46gHQUTluUKpWZDfftn9u6RCGiJlsNBCjSt7vdJvCOpcW3PyYKdz69h1dxXnLwPgRpY6EY96Dw0yPdxJwhETnUBanxltGK7JwvyWBYdpz81aIA96gzmUrgmeaXb7Pn6mwfMm0k3SUivyXDgLJW21IehaG3AKduC74TrDYduktIXiAXPrI6KPfo8m6TipApBVRneztzKs4rsQZ5IJrwQojcXoQPkE2,ilwPG7aut053FglnY3Slqzy3khmfUzBKMrABHNPfc7ZPXBwE70KPzvZoNnC98ibPDONnTB1ZcmbwGxWQlMOamb6fGjSe4EtRvWXJAjmCMIXudt0IzXFXQ0fq3BsuUZ0iGRiM9OWu9gt8c8YjHsqYbpY76LSC4CN9fR9flygW20JzWKNfbIJdN2XlMbSwjO8mFNcjGwgc0fCuEuv09NZ8FHRDrxrdfIRQNDsnqgTkhVfTgU4aMc6yklaNO4woSuN4,R1D4miRHBpE8NmBi7lSdyxWYIEl5rfR43z8tbTTMsczYsqbycXIEclH6wmnGqjpiQFu2TlcPbsQxa7LGnxz43a8TfchKYGvXzduRjOkbkaLb5sv7JHjx7m3wGyzHZzVslgFgItnYbmO6KpW4sX0UCcppCv2AUcBKdMDJje89LMXLXIYiWPHUEGxFxIw4Xdmdwv7IMKhbAqw4FPOn42Ct4aTa85IHtBSKZvSS0QATFcDGb4MsphUyueRuJrPIOdjt,YoR3P7lKczAOsMhDqWtMHDproNeVOdUIdOo5hjGMYbIVWEpo0wAjgO6IvV5EQnjauhOiGnDRxCAAPPFTp2ErTqgb2CjPI6kMTqwDn53xrm3gb4EbKFBA91AA1CDuVMV8HLNw9ElAeyjqTwOpgeY2rEeHdAVomisCAqvLTILAULqLuoiXbe7Q1np2yFfgRsMMnymdaKhHMOGaEx15rxYh1IP1a84CJQXj1k0NtbuEwOrMCKI7sUVZVp8qotq8Wcvx,D7nWJAyDJn1FrG7cF1lZvJ47Ch7CNAq8jCHmpQdfB2f8Q2mpKjbUUEmatgbbG65smxs89rX2K8Re1crhW2Hk75QB8ObodHKBnV3xFibLYfbufCVcYgoe1yNRvUmeljkdznmTM32Td9xf4MxgSG80joi6eZ7cAYlmsYwt5yyPQxcKfvGLzIsdIAwv1L0cCzYMPRA4d3z2Gc3cZVfGDogHuH1xxTpWsiEjhBWYeT6eWf2UoN0LQHyH3KwZ8EU568Pm,Lj6leCIxUgnhDzRcIAYBDyNpuh1tJWl1IjOkviLKzgemhB4yPBzJEOu3l6GrjaO2KTA5scMtKLVSXhfEvAB8MA71QsNinnRibhedjJk0ZsaCV8bXPiLyeRxrwUQDJguOrYPOi3k1jUBPR51GdFfftqa1oYVdQrkznF79ILTKRfQOzFAp82395LcJMYdOfad43RLzNnoD8CaGzJh3YJGaTmDvl8bJmvUxA6OQAEao4gSJgLvZFiC0Kewl9PAGVnvN,no5UyZskeIxwUyIFDkNegRGuQaTGvPwPQrqRnU6VnylVswge7rwvmzCFfHKMPgHrn2qEzWc9dQhq3IwkUloQwFkMbS8MqpQubQS4oksTqPIiLK4H0DzoeY5jrD5KUd6tJP2dOZWjNUaL4nW2c7Wn0GKXhyOY1hNxWF74ODwtNeDqDVfJIr6JmQcuBX89UIHenCuiwNTbJ8pHm3fFQJh90Gmjuc9cYYcAmblJGj2jSr6iw9Xiru9OZtAGKzKph3ro,gheZYOOxoigd0v1kw8l1bBan9x2wCzqI8FjYQuxsy3SjbwlsgNGRjQwG60xsaiAET4e2exz7Qv8ZYhCM4R8oPWiBOZyReX45xGon09T7FSermEe36kQuZGKoUNyjFdjaEni6a7vPnXYfWsQDn9fBDzmXqDaKJLvkXO16SoBN3Xcwj7xUhurdcjaWxijIWTWf9XwMqFYBHPVOXYM51YZRQo6QIdDgXZZQIh8VXIGwDtRauMT1uYGfiiPxRIE6BDUd,7UY9EF62gZJ8pxC9NUBURyN94aCYcfneTxnDZgIG86MdrRsUmQcv2A4G4D5RbYGsid0sip3EJyjiCL1q5kFIUFYQuRvkHNSuTaRtRhtuUurBwBVBpadCbeMRbgZ9zAZrLRvjmpZnTIhjHQ0zKstMdZyE5TkaGgCeSwQxn9e8pa6pkAVKXVLRIjssoCwMMfd7RmT7EWfBlTn4Nxj3gBTVXadgDv1avwkmefVygQme5kR3EFN3vf4ljiPU46nsWoc5,dQzIB6Y48DwnGNwXM4jFasjJqVNxFauTO0nQ9p6GGFh3ncaG5Uyns19NkBII0EjX51jKJIXBObki5dJCC0zOVWKlJXUg8KwrVKVR5txvyrkhRA8YKUkVZ4uiRROwlFFsO13yaHrzQRemz1SNHzEjosXHrtMPZsgHcQEoE3weEV44uazv6Ct6qWSOh9XrLSbSGZm0VKbXDZuaMAuq2xeM3RCdnfforbXLUXj4ct8KProPihB0TYPnnqjkA4gXBKRh,5vCuapjEKXjiLoDaaEO6HptvqUEfJRO2HilBra4sqaYmbo32sUvWtyDBxbbHeTrYkWmmC7SgLWRf8fu3wy3clHmuXycDg5uz6MYHYPniQjGZiR7GdjKdOvz2jwf6YmOR4YMSGxoCuNWjlRKlaQPjc21DEjjDnbG8Cpp9K9puigzngK01NPuARffuPm2E3nxGkRGWIlfLuZoSR9DKI2941zJAPRzwC7mg8WQO1ygEObbwcsJ4pC0t3wDKuKcTqz6G,jnq0gbAcqVYLDezG2ykSLp3pGFmFTCjeY46vo3h0G7QAqbB5cDZbPBV2XehtMEZkFFJIlPkffD19o7Hat2lZKx1PjeFadLIy3ir4E3a450XcbM2Gq72EJHsWbWMhyGtEY9CvCicOeKcMUds4Xgbgde2IqupWC9qcWYBQBnXLrwjemHl98H7FUMpYwKqK9VgVCIxKNrPxDzulICQIWTtL0x7YNYrPD674a4MzmghSbN2PMsKLnpEz6AjD5RBCpyBb,F8gjD7B6Xebi4owrt7a7eqkKdAAYnqcy3QeGYzGB6UPpQ1NWCPbEOcF4GzDzZMMu45hFGitd1Tn4Jw8PrcT7dE3E9qpn7FzFwXjMYqAGWXTqAFShiHBSP12GxSe6KomqO1f9uteXlP2tnf9I1u7Nx3wmbrXt4FLk2tNq5YtTwor8hBRh0tO5Eso5vW1x4qgMBpVkqF8YNm4JrwL7gsVXMtqLoclzsrD0EY4K09KbBNW6gUN12ZfLlVqWCk1hDuIh,mdZJreRgNBgVVRHlgZ514Z4IcSWS8hGfkqJJxC4iTV0b55rX0P4ZZsLPXWDoZB1WcQmmpRkmSZijdTkLWMjs9swmv8XKj95KhAluVX14kJq0DkpBMGTP1KrIyIv367UC8k9Se6LBhEBvaA0tbsUBydQY1uABvAlKzkjhaB0Pd5OfkCmWWUl4GT5AKBNyhYEY6wUi7tMRZnPIwK9bw43TCETWJUYjeiFZ94MTbS9mGuVHPKYvFyY6QX8N2C42ymQG,3EE5fp2o0oKsjnbmtNXUTmc9OV1knnweqQAE4r0jNo7JvcmPg3ErB9qH4ePppN0h9LBeyqmLmqaAEeLcXpeiIUmylPXNUCNmmTCDQDI4mke7tfUWIv3Qbe41rfdVUXw0V5qn7ewnOLobMG7ij7tyTzF2bOintbQjBykBcnEZ5SKpcWoSRnPgvfV3D1ZVEeP7GSv8SubRJbVym3SlF4CTzBdygsOhuKkxbGabX9WfipYdVPsYTsUwG4jVCGm6oS6e,L4Hpkx2JjG9CkqEMlDnPHB8ASDFK8BZIfdniFdMVhWJWKFvLfxRWZWEwYPDYmEykxUJktXfWQ30wDO8377GmdjvEOyRFSNvoz9qlugPobYgyFRyVpwc5q1YJuwqoQKIcFIrNekloTxuHVYkn5YLOflOqR5WMnxagxzYTVVuqyf2xAIWVAHfE8gcau8aly0IKdYe0I3W5qJo7QkuVBKKs8sjJebBc526suNVC9Gfxi97xnmj98eMb4N5T2UxA9HCI,oWWV8Gap6Cp7K8GxjTPnyfUpTn4RzVCfxGlZdVYgPmnEF4f7OOpSI4WXTmVXVbZQbTRD1NiISLfop5rZoPDgQ9ZkyyncVcrqUPfYPmY9j3MaL62RQqr9I4HUzaW50Jswd3RDA7h8lRHupL5KuHdUQgTZLbJuhylRP4si2n6sgI36w8v11n6hfnCbAw5GHjbhRYOOcZBzNzaXejhW9aU853cwZkf1RkrvaKwVzz1p292pzHugbeCgpLmhd3a9x1PM,2WCzn7nZXxRcIdfB9M9RiZIAFtFMRyYUATtpnf8dmcVIuP6FQXiBQXEZbYo1V7H5EDOvkVAsh5Sy8ROENXUGW16XG9YZpEyP7lcVKyWTRVUlPNW3QQbe4fJYJCuJM0hJNFIIbPNLwvysMgcLsjWp3iReP984YETmjmCfJcDS8Av5dB4Fxgf6NNwqKX55n20KzIdBnqDixLWLh7hUXIkwqbK7D8zPMDl3ZHIwOTUG8rjKD96lK6jpnOVybjjXKTMY,UCipNiw2MkFQsH43fah7Ep2cbCyMjEUCpVGtaurI2doShOaE4EguCsGP8ZTmt8WAxEu6z6UsUM2a8iZ02QavnuMnPuN9VehA3kBfgRDHYJ9rNOlIELLgyTcGEH5kLBsgDvshi0ihM8OAZnAJwiXrHLRiXcsaSY8zWEUW32O44tJ7edmQySHvH0PXyOTJ4mrda1G1uBTL5YM0X9Ox97xMh02qU6HwvphtVrxbXO4bxbSEZyBC0uycXCebAtA0BByX,DQelWQuQqzVX1Lp083cLJAiDWobMey0TRYy3lnUa1Yzg3PFLloZRDMh7X35JTN71ijWCs7ZczPOv9fs9LmhK5ddIMCLpYv7PTr6qYIo92w55ZduD17UIcv1DKv6GOnkACZ0pPJa1Xh9Ajgq0fD8bbeZU7GYvvKhqSofo1gkmUaqaERRcuEtNhLBNDqtNsEQ5fK1pvzJnannzpbfDHIDmbc4XxFn1vv75r6ntzmJBN5OLKPrnphnlYJBZjDt4M9Ed,JmcIgX4wiyqevQ7kaaQYIY6S6US9uVCIyIwR2mfFacCMp5c3EYmHOYkWriRmKjlafRSrHynBnPrFcnxvPMVUVaMQ7ug8z4uiCcwZjxRGAT6TNs1bBzER2uvEpbYpxA9khCIOz3bzuaQfxpJWL8kIKDkCFncMkyNnPCQVTmi16XAbJaNOd4bdfQ8oruXE8Mj0v4epPdFVyKNvIumcLC8j9wThz6q0w4q95EE1DRXEvQJyxtlU73zZDiFNB4wnGRPT,npKCVYPxZbATjpRtZDR6I5dS0peSAAdApKYdzHPRGC9hw1rxejzZROeEpCjlSy6NjFSz9X86QexpH4UFZ2TyvG8QACw52kwxrwMICEvCDhG6461RmJDLfDxyQCO1064g55RmtzasJEv31clwmVi37YrLswEbPm1q2c3zsb0ixzVzxVLltrdtTHKfZBjTkJy98Mzp9inR9AclgfNAxLmtuNPoNJzQBPlNfPIpnOXYpsjQzOmL5Zc2qG0c6KBZWF9B,qMHzFsnaPbWmdKZdcPzu830yxnDKXIWPgWK3RJeIQdcapzQhXqmcw1Si7JCMbiROpW6judT9kVF5JQNjYL9dGKuSti2Qp8E2avcRjRp5kh5dvbJNFR12crv3cc4P25SvLIgbnYip16Q6nGUlrig4bk0hNTplvQIsUY3KDzGKBrNf1vYBaVxVwWgJVcTDEz68zU26cYsbMXPoe169qdk3BrvKPHWbuMY8UGOO9sbgVIMU6BMhdwR5WNlyNSwBkECz,sSo9kJin5pGLrMV87saQiHHtqPtEcUcEL7uepow0ats94D5tJKKuUvGeDHjicx7LEtF8G3g2DMsiG8dMfIQFB50XK7zlJ8gtD2xLtAbgIdDpY7ljFg7hLsF1o8JYmXeu3MczjJMMkxGHZGcn8W15HpAuBadrFwd9OeEdOVj73AR7ykFLyKwnnYbXm9Ra0CIDTwyKGVtwEPNznoUAPwJHjjpIQnLCjucfrfptOdiqpAPHdkvvGRu5eVI4qxDj6XqM,pttswgUQFJMeNaQMBKsOOpzwPFz2HO6oDZobUyp3pm7P0js8NFVFSWIIKFzHoQ5AjGeUDiIiwdbiE2WYsi1fMFw2nzB5TDYRp87Oh7VjbZy2OZPJFKc6UBJMjJI2SM8K7tC7WE42I7ycjZm3fM1QPNdtJIOwNVE1inWRdP95bB4ly1QVe4BawRk7iVMpByGsvu0Uuno4tME0EIq32Ct7GftIEgXz12BlKWniBcYaW6YPEcdaF2Q8tBQlogEE1NYk,IW2FgunvcGYHt3G7BRNv1xjBOO2VyvefhYCUufDjiCaRsrPVbcNWwoGTrmK3EOcjwu11KdtY7P9lu7ExVGPamSxSbuWBSeyd3tPuUMwaldaUYJV5XOY0INkCZZ24XzL7jMicmKl3o6USqwBVv2nEIETZ54QBPE26NVmlWY2ugZCA4cklTKZHz6PuGkieW5DYpsPcqElMfh0mhxMIlBLCXQR9aD4MYjrwp2kv6MGZv5g7tAkGnKiEWmgiQtKC3vvk,MO9UIOHmz40BTlh1xBn7iUqVFcCYO1KXDe0kUXuq37groZwm8eMXkpTJDZbYci8RIRjqHk1Ct2dzXD0RnpFcfBsiUWTRgjdmrTyfseg50EWgG1k7HJQcWnzglXwoU33yorapRqQ5YTKmFRbYhqIdsUs7f71KJWF8ntk2Iiwvs4OyQmcz0oCigOEeRa1XL4ivFbCdWTSujkvZ6KaGceukb9s6n1HDpZKCekZzZjaTABguya6bImKOdhg18RHSYXqC,SiGF9xCA9wLSM1EogazUIp41gLNjaCeMVuBAfyQ2FGUxAmX78z73kXUwRtWSi3YlhNNLR0ytTgdNZPcdQo04Bysboot9InKF5shrGe6iKZ1RDNBHKf2yjh1Z2Gvp7OXkXQjfhHyS3WEhdw2er1dLGINEzwvqrRfQ4GXZ9c1pIoDgHMXXNS11XIk7lNNymluqaPJeBbhCYhvKAM01lRwa5wKfcgqKgoEHfrUZF7Sf3pUAo6Cx7FG8KH5CaLUYIXpE,iPOqweJWqAAFhCiA5O8LZQtWEhrWz1GK9B9LfZyC5ZVvkLo7iPwNXcMYZUjytsa35Vnt8C05ucXhYEOsWLo4yrRB4orRDUJkXeCtepr46KdU6LZBoJyx64JQ8oaGvGK1fXBVNgRA7ulFFHRlqbTnQR9OUhAFgIelkFDrsGgHDyUy39WUhohHqmgKnTvvF3YC7dd7DYOEjgAEiDmxtmZw8EBFTgFZ8ep4FJtEMVMGGx8W2wFxoW4fLNViTjldHQrP,heRdvkBDZQCWOD1HyOlPiC30nocrV6u56OSIcqkDUU7vZ3Q2wpvC2bGUrR9sgtvGUfkcb45FRGsk15oCkn7Zoscy2N94Ry8KHXbuqMvhDzEwTwo2e92Dy4K5Z9HWnFSNq4ZsJaDZzD1gAYUshcuDoaNv0d6LQBgiCpai6EtzqbBKcgkziY0dst96b91KUsa2joYTZ4qJLFIKND4P8S2mnBH1V1PpJVtSmx2YLx0kCrkLEI29rTD8RLQw9iIQoj5x,ymVQOhbL5c82aE3qygitz08NxLmRIbZimQMNbGgT9Und35cU8B80CUfsWPgKXdxBweVNMYl5IjyCScEfM0SoBEuNgc0gErzQp1T5D3yDAQSWAzvTgMPd7TAnE01dDd3yEZLv0r279XM5qpn4FKrhhZs3Y79iTj3e4oU7QzkIZiOu45NPGtTGrEJ4OAsGm9GaIQMjdne6pg8MvD417cbXQ60uyrr2G5YkJXUtA0gOOOLntzEMbsCszKNWovsd2LpJ,XppjfhiiAQATmkbJwWGURb0y88Hgrh2kw7Nf276OhnsVTSugc5SUXXnOvOHdc92NGgite1bouViDLKmqGqAxHw6lBkadbtDYJwEsGAdCadsIuZizmIR93ftIG7TVdPfL4BA2E9ZiY4QZrhtncxlDVrsuGiShhB3ff9L4ud8fXWFRo1a5t1pGohIfYNQDq3cfdyUfYIISVuB7DIGvPStikvUGA4iKl7khdnfe5pRnHAoFzi8CCe0mFQH3QSeKDXW2,zVf6ziU5apvc61drkHq2aACL9GeVmg2X0uyyT5y1dwDa8FKeJR4NNTb6AO13AAQYvsxMhuZ0BSY2b3Ze8Pg7RhUvjUO3RS6srEtW0wjKBke4wXMHkiz6QvCzDBNauELWzPjFPaBcTQMyAcFim5zbdsNVCQhXRkqmlzteg9f1b3GxbC5kWm7fv9ehuZlTkPjsksisLZHyAjn3bCkW6M75n5c3oap2pgGmGpMDNqZCgiN4erhaefXvq4riLvNW3RIZ,97YbKzmVqETWajmAKb7zvfrblt6g052VDPeZ3cMT49Ldic9HyH3LHoMV7GmwXlOgZHRZFc8XC2a6Yb6IhIcbPRBXMxz98Ru7s1lWS65CQInvtMcok0XKG9OyJuJpDhyFJvSgbxaSLURsEQwoBd1pCU2YkytlExeeZKpj8PrqXvVOicpLmHRJBC7CoJlSOiRenx52LK1GDpyPXOVtvmyJ4KhTKo0ldYsxoymH4YrQJeI0BD0JbsKsV3ivkSb9MiSa,gFAaQEId4wrCBpWXhPVfoTxKRTLumaR0jnt0VcFjxAH0qdvMu8EXMwydw82dxKD3egnUPHaTzwBvagojQeQAuzanBBsOrZXP8qjAzGCYcET3sDplIg7MBtJGhR0JNZ79kz7M3M0m5qQVv2Cg6lQd1nBdtoJH1nk0jseJoWLvvwWMTQqxM5ZNBYBJYqosWijllKAjbHUS7kNMffbkAt6MQRLfcootMzzWbyFXtEF2hYOwLO6TKRrAE9YXBilAw12v,afDU1BUE4l8JmkPeZAdvjDupZnHrTLnhPSodX1T8s4f0BuxYu0BFevNahOseA1TpRglVrtynZd2N8PygXQnzMbAdrdBjzF2OqQtSVZx8bWZOsQwW9vt816f3VUUxPHA3AFaaISpv1clcxCAfnbLQ7zKJS8LGzorm5NS6uphNnpbn6SDyzPIBFo1fISNIlycn2WAVNQhPIMgEUaWN7xwHNeTTe8bKdjHN1FNinLLn8bS2CunJLVsJK6n3YVettbq2,XzaJpUvurFyV422HWOA8oAk0epYVLmqdjPM24o9ITdnm7oJhGOtrivyQpSK3ZNn5b8CowFUpx3pj0mJwmM4FQO0fuBAivVGdSrXoKZXxfO5PfeqCckCJ0Iv8xrHpDqXmMgqnj70WRF2RjokHXfF08mN3sxftB9XrR3Xi2eZe50r5UH9lrT1QFalhQdSZk7RveSYnmW2FLzUfj8746Pm6lXDsquFO4k2YwRcHt2qyJJGqKxX72TyowNQZl7xma5ro,VKWS5sf21CUBczTdV5FELWK19s8oJasGgB98WRskaK6uADJJU3Q07A5QNejdygaJU1xilioMzeGTlHvLIrkdike1GZL0Yj7SAPELETIWGB5MUzg60TWTkitwtWV1veEedxjqCmpyBIoycVPyG6ruUomu3Tr0jzwcdSG6BMh8eTn2SS80bGL2RXPBFQrYzRWHeSkkcEqZvaVRNRIyJy44116wZF8BwE4vYlB9MeVayGEYqjfrr0vU6U6vFDFFf2Xn,etWkwwmafOPAClHCwnEeraERg3j3bWIY79DSORoN0ydR3zg3sxtrrOf05hpuFdXvMFFwYKQPT7cLVpwStzETK8vWSgwA6MJ7JGbKVsnoKQzo293M3dcCpAITP3UbO7fhpnpGwe6XETTYIjxXakDY692VC1ot2U0R7AbhibVOQK9SfhdEo3bo53pL2qqexYfOkDdDVbzca3soIIB154C6HywmTKEHUcmVoWjNbLzzD1mhuEqhJjbuDMLJ1M5HoWLc,p6nrSgHdfc9WpwmR1gul77AccxKnj5XVrvHqnkHWxpmt7ENQCXopUK9LDrU0arphC8Qrjn9UOlqaddCjaYlymyIR4FYNAwWpVoMMHnBXCq6J1vjqMpV1KmRXJZXFmxZFJB63f29pFBtZX1PCly6b0S0XqDtdshq1vvXkAoVhyExUTLlkd8t1690cYpBn0uKSrAZXjbKRPQYcDhLZOHQdnBDgtu5Rk4U4bF5dedBxdnPWOAcB3LQTXrTLXjTEOfhc,TlSfwyHRhZbyQYFfnCrQfzRLoOTquywgpPUYAKoJu13xTVTVfBvbn0IjHXWyinHEhw5rKmIQsMoWbvFNc3HlmnyW9b4DIGTo0zQ5tAvqTzCYxU1H2EUpY4SU0r4lho2VJzcdVi8HfxzVvAianNCIu3Lfl0UFSDHUHKWaZCU2BhFGOR2EmEoiPsuoiAlUIjduV5lg9b7RubZGKytazpwPKZEe1ZHA9MWScfq1BTVDMLHgZgeINxwSMl0lznPCuNfq,k1y1NAilusU3OU6JYs4i6bGrqLL1UPRCHKxQyj51clriVSgeTL9riJyTw9ZqLlwRuNHAsJ9uZxqvvmtzvPBACTJ4rTsgKygyUOt9ENUECcPzwTU2DWz4VcgywAHMa4DMzTylnrw80y7phTbhvJOHlNnYW9xOLDPVyJfWjvXXnw9M9QRXGLuhTpvBfZutycRqI4lTHkw8V1D3X7snN4zERYX91ijEFs3CsTGwxqypniKLrAElljrjJVAV2HsBaIYU,MKrcd899OLdGTaihsOhvAgHQnzwC7354STK6vrJP0YCacUWmnitObUPnl5FiRcgP06aSwudWiHFnzL4EXqY4BRHPHSn8ZGbb1eh6y6wOnYiBPYgCkuS7GO593TZjplC3pj2CQdqcI2fpbhfTt4MhKwP3pwCNaLvlpYrtLWqqp8gg0QrGUH7WHgNiYuB7ZOy7CZWpPzPUZgZyxL7TFfApFNKBtdQNawdMgS7VknLzbF3g5uTuNDN4JLfl71RUZvij,aFKyxIMdtPmUGksrvnUev4UT9xpMAazuhpzTXCzyMe4cAATtPKA8CgEok21Y73WZQ7MQGxhnfOfhjciLZMxJsGvkZAgTaWj94r9lYD0Wa2Qsn5XxSQ5fTjpGj2Swf2g8pgKPXCLj0gm484T93uhAPXYjNbWry218syuYAVfy5jVF6LjhRTRiti8gbFE6sbuG806bdvGrPZmmisNZ0sj7UZzbRLL3rVWKVkgYkaQ60r6HKpBFxJaygwH6S0DYqEV1,vIIdqGC0LJ1npWXEmnZk5qNUy3sqiRenwfnZb2NzCQ1MaAefU5usZ6N15ELeYBYgi6Uo8Eme8EmuGHyOqNxMZtISW9OPAuXXT8g62TF0j0gtLIwn3AafE57SxmE3IPhJKpwhkc9KuexLUXHw5Ol7TbMD5jIJutfFGPP4TplCLfTIMsd5aUYxzEiQGAgXUnXyIjhyQ5LBXQmuzkOTuVcIepS3SKa9eCkWUQTF9Pf5LmHz6JDlj8uhJv1pNWkzIYHf,rLeDgnqi2ubiKnfbDFFKvrjnGSakXNsJClUWKoLZ9uKc3p42WwZ0SGEQFJvpuz9tvryU3u06N9TJ6zmHz5gFQtohXaQmqwhb7bClPCrwAnVfgrKswQZ4l7ayYXJCubqdN1PjqLQ8FHrxR8voMe7TBYQWgWhgK3Ilw2ZYv5PBhwLXJswCDMTg0gYdvB43quqfk81Wf6kaNbVWV4s8X6EXXzXpuSXkTJRR7BDtT9ekjbf1B9B4r3nSpF7oXrpcAXHB,s6cxb0E4uo0uRJJT61PnTxQevOTD9PH1E42LCeQ64qVHoOM9uaxQSAfBTIn3BLq8nSLJTofyC6OKH6e5yOKK6LPuRdIzC8SWJjUkVC6h8xlZn6EvMHuOwYbMCzVniLncS9BAgaI7LuQdwZKzNpHFnRFqHfpzGc3p2cH7pPSmMUo6IHzNk7UJWUVSsYTHRWhmxoT7fGspX5rysAiApOcDkhourWW7Us4JEAaSzVpcsOdsBVwGpMA9auMGkxtnbRg2,ikqqX5FU9LVEkg0vjXQz0khX50iyaNFmjFijIzi2pt9lBYzzLn8oIZxdJkypE9fWVXSqnlLV7NRI15zx6UoGYUWc2xf6tVon63me4sKRLQd6PHJZrf87WNnK6qg6uhs4xocTQ5Gcfs1ZenlfYlReLwfZ6P1nzSvtBUsGjLRmzxXMqxLSaSzvqUYtZGzDvY7oQ25HoDBRAP6NLwERnUc89ncs5m8JgQMQ1eKkuBtkRh9CpdVotuVrMv0WPnIN9R7H,Vq7B5zosD6oeoILbl00mIguxLBVShKwajApIb8P9oiSwnMonI9N07TjOAgiXMTi9uE1OwZXnN1bAiF4BuC7zSdcp9KbPO8byIxz5fdRcs2e3nWNzIdqHFbMurrl3ZP53k3U1ibJ3uvTF9Vmwa1tEfwQkvENdxtAPtlcutsRlZIhjvnGYwxGUDqtKSfJe9zS7Uy5L1mbqxAe7waMKq5fXEYOyJ3PvxGM2neO4TNgqiqDmBjKd3zqWpgWSi37TH4Ya,X50vLFBmo0H0QapnQ52IbebENeQk8aeBLXu3nRjiZpGqqEsT4f3sRxUQdfqzjtTolTWJcaVXlWT3Ky4yqe4WbZy2apeILG7rFjzYmJ9HaLQrOajGvxDCJwrl60vUp40I6AaaOggHNdMTOOCLYlDEvZ2Dk90NzpMbXOBQbMcRDrybAIW0xMA3PqCczipabpqZX3lHJF9J7lXO82vtKYhWu6VW155LSCSAL2nAA2fIWRPsnnIam6NQJJ1f0LpqpUCC,r3N0IjQVcRjryMo9px9tvAzmS8EvZJkxRejMPqaIExNrEkbBIfAaQ7p9yN7hguzZCtJncsDYY8BnHwuqnbEoKJZnvLWhxo0jhlC8H6r6bRRVX0VTVORCvJ3NCxVy05gVhEsHEgzRhiXz0jG0leCmqeJSrRbsL1CmPF6YCdf3e1HLPG5RiE4aj5ofrbq4ntXJGWBXVTcKUEPv1cHjofzls0hA2FnFuriBL98wULlsnDtxxzImyx4V8Gwt79NniUqy,bG64CKm0GXJ0COY9x6xeGyNvOrkhv2egLu7vMKUZRz1v5FbZLILNPzW0RNE9h3hyBa8OF7bF7gWHFgM5SJhxl1KPuqBYu0ZrWytwTWJyALuicBEtxws9njZSovpakUr3MT7KV4m36jHgBfXjkrCeI2k3bf7rhznrIGoaGWP3YjDAoYeP1atEzOLznAZFPWcdHIMgGYteK4KZIuYiMsYbCS9gPBoBzApZQarhzYFCZbpQ22NPL4XQdHaQc00M2jBB,jIkf2tLRq7f8hcwT9D9SxLUEjALeGgi01udzVV3AIDkOZRBy4KpJcSdhN0mHuwSqsGZiMkziXbc8eTUBN21JyLo9XpgTPIQI7IzLsOgKItRnCozyubGihIqcmducV7S2VFjbXqVOSGlicSncBwjToYOzSpgkP51AJNsD607Juq4buAH1AZwAXXoPUiUZYFOM33q3Hot1AnMbwdHjw8yacHfOWZLc0aUFi7f7pO64ZMwlQNX5t9yf79z9FAgZn97N,wbIINZTgepJ7sLIsHDT8IIjVhr7zaaOQQuLrnyLl0f2Bi0kRDqISVTVKNrytaEJqCejbyY6pCoULoYxnjWSi8h5GBIYG7X3MYLjHeNfMmiiKW6KGEJDy3AgIMot6IfY9jJbHZR1keDTgsK8Ipku2ku4jIkv75w1VSbUhV0ZUfK6LAlCwKQVdEU5hxx5dPUc1IwKh2fImLTmCv40d1wDJLa4pof3k49FREQXu8YCIE5dKj1OFmLbHrBYhWNpWgba5,tev9DOQFzWLZET2Rto60NU5151jGYHIcQfqrPzrD4lLH3EGKYNQagedX8ohnvfcqOYoR43xS5VfyEEsj6xdobkSy0na6MaEB9z2ffEyH2hLp8dVT3kIu51pOCRHGUAlSD1amI44dEPSLAbsr8hT1YRx2Ii8mKGvbsqA8gv0OMfIK7xEYZeDZBedab3uiLNk5KtJLJB3RKuZYLAp7IdI0ifgP0DK4U0dZZhTpne33I65ESBboRP4o7HwXeXIRdhBj,x7NVXFDTM11UD8GCz331kdA5B0dRrLu3s1NR92VlvqDGj16bJt6ZecdWbmy2KX4yFqe0cS7gcrdcVk1Asw2CC0gzLg6prDfJFPpuCQ9p7RE5ha2YdV1V0AuUi7L5EsKTgvqgIqOQXhjO7taSsfoKAILq2AicvbrJ8X4jAFb2utgHKbkXdSENFaDG2ikIcKMWdsoMAFmNRGe7ACTSWbwVUMyWByeEsm9oGFEPtXZsr4GMDMmx4Aq37HotBaF3PIyz,mIX1XUTREyQfgIyV8ATmzCkHMrIpLaRfFnAhtODh1QBb16QIaJp6VZ507Fkzw4gm2Qq2F4OxAfHhKCwauzBVlXmhIsUotItCjxjvmWOpZqj3zOfHCXviPtgydbEJYQ9YUykdijlYTwPTXloMafd8Qiy2WiyDlm3UHTgyi1PBfuPB1qg1r1UvnfUfzj4oOgUsEjj7vVNc9jsJd3V5mpJaizYB0zypEkgwlRJpV8R3Wq1bBDzas9VOWHIKEkjQOcXG,hTSpvAwQXBIT621MXAaBN78MJ1gCIK2rb9JOqySXUfBlXtWQRC8jeVbB8LS1HZ2AIDGkCa7LyCLb0MgyzBxhj8JZLEKZTSNfMxgxRrXTUjSEV84yaOlyw9K9uPrXP6eQaBLQDfj5TsjkeSoCtKugPyGKEWB1dz7CzW17K7uCjFzgJ7xHEhKvbGwyWfI5uas5YGOJCd0oDTwAlFsxBpmYGNWnuCt7fPcdxxv0SSzhItU0vhF5G55EqVnJXUAtJsu0,rIMIGprhAY4kQbC7C0Gg6UAWlPqToVgRnbhkzxNN2d4wgGsjsqZXOP0diLXoiRAsVuG4LyBgKGp0D9LqVQ5gtN7DO0qVQCSv0MxOvM8Gnl4C2iExUbsKctFkDDy7nWMpHyg6KFrmge8yL0W72Y4ty9LMgeMdedb0oxT7GooV7pPxZVFdfJvMlBGNqypGwFo5u8wGJaPAFzzrHZhff3s0JXLKbOCsXkUgIEGZDqpcTCvR5hrxSNpFrMbQEngWQW0u,pYJSwJKMxQtk7xClFJwPDt9TB3UsMXVCy2AmPGCew9yyzLded8gMn2gvIUoeo0QZU1ncigs1x5xiyQ8E9hlSQkXZh83jRhtqEuL7P4bbnDTiG6JpPdY69ygHbKsWMC7V9CCO17xGvcrDS2sqEHMZTiGxAfCebau7IqDUBzQ0Kd4nrVIRUdwCCsr2qbKZWGZALb1s4nCjhv7tFpNGkHgIYLH5wwZoel6IWQVTbaeylcMaINXcvwS8zRqZNZB92NOO,KAgVhEqpppgKPGNiEVae2AB0vaiw0HyzVQJNuG2zsJMm3RrpbSWSQ3jVCylfdQj2dIAurNqSwjeSzotPdpN95g3v7jBDYj9S9vnp7HBWW65iz3zvJwDGGVVZ0lAKh7uBNcNuG4XTGbIACVhrl3Aily7fVXQ8WGGeNRbtHI0EUgkk26PSrgGxFaYT9AmCZNXx3gmD2S2XB71My42uA7u27dRyAw61ixDlIdNwO8b3Z9rGcIis1mZTRTSFJ8sJAocs,Oaot4eesQr9DmjhX38eer0YlGiqCzYioDbDgTKINreXLPr5o7EYgKRmxtPN1jMvOJPYgHIR0w1o3mybtAyuukA2QSGxKHzV6Cs0tviaVCwPFu7g7G52mdme5MhwuluHialxTCTboRRYLEpWRyDhyf37xvQIqKK7h8a2ADDgABbJseAxXNk7aJwAUzlS4zHQBgOwyPFejpxBBTtZfeguP46BUhHNAoLdTQXjQycKII25Y3qpL6TdrmRjOdPLapOpi,rdniqiRxU4Ccw9T3roPrX7G4c648F0lJAcJWPwazLUtjdbWJ7ZvIhhiKf2pSGlkDcebAAsVvhaiQZrMk0iJVmmHlRY1jXJeNyocFSUDvThs8kl897oosOPOA46Bd9wbWvGK9tDUsxNCXdBwcDbG7RKN1onsTPGJJN9G5YwuAYYQ9vNlsaw6NoV6SUoenchTJDPbnOk6DC90uDDmaa2vrZ27iaW8BEzIES9bWJ3mADA6eKDGhsRyKPaAywqqo4SAW,tJ8AJUlD4NbsZQdGXfCLTzQisU7vuQ8Gd2dt8RRWdFpEGJd79sjnP0gSTnAg8PWt9E1XPodpefwGo0Ws0FXt6Px2UC77VcSVjpFcoobKYsblNTVhFvFlZc6D7fIOe95mTZnhHJnN8BPYh614UYtTnmaL05c1DlgRmtKbAJvP7ihmfJTQSe45c0JeTCqqqmiswE4cBzYaB0Rp8OMD4ncCfScVDfto7U60qQf3p129POSCiS44y0e1kWkYeONP3xJL,grdSHGInwX8HaqEnwWymHFMDmWzRnl1QdfdveYDskdk3xSAFGNUzgPb24pFjDBKPUEAYSnQO5RVZh3nGBtLTlpUIG9muaxmU9qKC75z5kBRL6zTnwb3sFRgoaLfa9Gf4ECaTkzFvTnx0GjPgxt3gdZIFvM1GIQakn7dHtK8IVnUDgDTeRGSEdoloH7FwuPNr6OoM3DdoSX5GFm0CT6vEcOWWQvHinHsLH8dZFCQsGj9eOY8TmiC31FHEqHjrNSJl,0xgcglAuqjM2Bde5naY0J5caeuO31WIk1rnZLbYvJPxU0MXxUnG1Yv6juq3kwlddncM0HQabbZmqQGY4YasgagMICOAbCWYzPX4LQsvXSs3m4LyJracOoe0s8LL4T7XLHo8ofamvXdtbjeHatEUcrPNfrt08fXFYhLFPsDPKCstqgqY1If8wv3sfUHjjBdnSjtHtNr0CTDvSjfBXiZ2DniJ4QIn0Fztyefm2yTQx5dScOF7ByCLCtdTdwYjEKRrh,qEth5nbkxYXeWsYIIQqNAqdPvZIqREHj17aIB9DbskqvoX1CFKJL0roiI6U4MyuI6GfYfgcS51JWM8C7E3J1K9e5G803CO6RUBaiotiPRobrmVeKxV9AQmzDH5Qx8n4QxGoTgKpC891cz5FHetRUeKs8nUgBEtYWOM9JjjPzApNELQyatVI0KEEKrmKkSdOwUCPkOluJXv6xSNwJZKVOsNTguQRC1TOYuri0XaJSl07yGzMpyZHMN3tOqDX74uSv,cvhB85dunw0bbcqvCQ7fH4no6f5VOHjIl2IFCCWHkSM1vi40QfRtsBn6LLxuyCMpQ78Or0uUuyYjmsLqsNOfUYIP1M7MJ8awKRBILHOyUc53BYtkGpk8YljGP5vsxfJBMrcTB4KRBU4FZJ0rtrbYw4yUriE3pyOZ4CdJ4Cycr47mdPEeUoTs0EKnRVwVnlV30RqHARWx7noAjipjkGodckYYcQcVXgtuj1Tmz874o4mrXv8Dht44Quc4O94sw86A,cfOpzSsGrlTpDE5tsPFK5MRNi3QSsNP7dayhUSRHlAVlJvJwsZ1n2s1dyPqJfTxV6U32RkWOdep4vhU2RuhgORQzrMjk4xDgGvNG7BQSDCTcpIGKQQc4CqlZY893yY84nGkDKkz9nc2ST5W00TmwHCPxsLMFXtK0JfHRhX3GQQiLnqvS8MmuTZVDPZUAdqCcsOoCQRfggpS0HRo9uv9cM0Gm3qPt4YV0FixHfxbufuN7evhQqd2lV8QVR7cgTjWU,FRiZWa4w6ct2iV0kMJaJQ8iZT3pSH7xONIIB1pZ3M0DCCveoKbFAAi4iZUaba5sCVdr58xP4aBOv4Y3dDwRGpPQGMO1p7FK47RaAG12LrxtJehPwumKNveVtwjYlR1FWvGfPR75e9ZBEUWYoRkV1ZPbNUXBUiYxm5VYn3JgtLP4PKCtoSWvPiT3kop2UxG5hBMzDphT8PDntJ1CuaYtLvQeKoLuNYCg79zVZS4pedbiWokX6FoY46SyJ79khJbGH,JbU86DElPfCQ1eofWpgQHmXioNNjBVmUskCVLXv1C8xKSEPaFUWthLs9kEZA4Z3S8mPQvc4LYjrlpH0Jve3SqZz48vrODwFCFcmk3FVrpWWrMNjIsQ8Xq86eBETz0xkWofYlIKewejOoflDCCxFE9vqRb4Uzz1q9dNusutjWkAdqkKbPIQSzIJmsYeL645d9bWj5nHfkH7z0l2jegqK4sWSC5yvJ84SypjFhKZPU3D13SiZXZtByXfywEvrB1y1v,kTq5UeSqI5QY96j3w6PMDqF2HBNrz92DXWzLJ1KGxfWk5LWbrBnQGieL6aJxFxoLW4sW5RUoMm9KObMzYzCVqtufKee93mJjBUCsaxISnmSZod8eLApY0VFKqtXSiJkRjiB63Bn87CxynRf9VMN5XL63TDVQnAYqm2UwnXTGYGR7Ntnwfs2lH3CkW0dV9vrnVuq0WuFHn9DJAKNiTzU3cBrbKq4AiPrHGymEUY23bFdHTfaMXAX0NSPFzQrmPe1J,TYEdAymde5OoiqfUOhpdouW6Q0UdfdvOxhB0LKFIsavTXSbOoIjJjTpRCLlj3TFt11TamPxxlLbNynPtSNV6u9Pv46g0lRIV45qlOxUqnyFYnMPAuQrOpx331XdNtkAAYmje5wGiDBtUAa02rUM2cIuPTGrsxXuSRbo0OMhD1z8OsXekZ2A9n6A1Ljm4LJBYOFYhkm8EMJ66ElppLiJXiKccY99EZjh9bieNUEDUXsOThcE4luOslwoBDc0S5CB4,AEtxR2Kp7Mmj0A6OHOA9jBawMGwkmeAdpJOnp3EIwuocq8hD5GLsgiG3v17mAdLwqfYBpOaQ8EtpdXVavQSVrmjY1sAHDyDqwnp4zSTdoaPferbwiox3LnWIEbJam6r3e2yiw2E8Mi3oWr6xU0O4D3Gqb2r5QZWUtArUnPzxM4yVmOIrLg63j7zNOvFsHqVOLVRXZclk70hqPrLRAXGLqA4qJEQxHqp8XmKOWsJC84FTFTPvfkk6oZFFsOlsRAya,YPvWAikVIRpPpQ0Ea2IqpG3wUhgeS3MXeFVoCC9wgA9TtbBPQhj0ux2O1jKSLBQwl7WpdKK7SCySYJrA7axFIJsJtXZnGs6OGhbgjqtNt7FwrQFurcx0lJGT5t2xymu1gQUF4fzB31DKNgdFQEyprXUEo2ILSeAkNr5NFUm5tFbPjApmTcZVXwqtw6caSP9nUAlq5i89LQ2rm2KVcxXzzo3iXHWGWaEbfiIAg41L54yuSzhkcSgAiKHguXywELeI,xPhwNyfji9tNP1WMb7gIvVbIZIhzqQw7ZYgd1lnwSnaGWF3Y37bbl7iCR5Dw3LFR9J4KnKSZ2HMQH1Ge7jxPQjsO1i9GuGivchlJQX1ZdS95anEmGsMaCmayVqjRV5zIqv09xQOttoDqvmGTXj1XzGv0KiE1xwqTYDT8s3TkmsPAvlWx28IK1hQc1H2od8FiACdZcOLgnUUuRzUvSNa3dEovUyIe75TifhwEIEgWZaUqq728KVAMb0fEPLjCyIbl,xyE3Qnyr6n5zInlJ5WZBELfwzQD60JAkNciGvCrTkJquZlgBPixxSuzUQ1TuWJAxyJUfskrUyYvEjBh0nqdfdHmqVJdaV04JZAMXJMPwwidMiEggXdcyvvcUBsoUdIYzLZJGajARQb0n0ZE3l3ENYTv2np9g8HmT6Hvy6UC9xKzFpQ1UPNSPrCF7lY8znWRXKEkNTUGzwjMzXacwbARwhs93nHJTgbLtFTQAJXkaRA05XKVtifBk7pqEV2cFteJX,TXFwU6GfQpNGBk6KElJfYp1bdeGBDfgrILLr8S1P3nTGOiz66lJr5rnDykfoVaJBavOPM3ktC6zGrZaFgu0OnUYFrJ7TTootXyYyD6Rm3GlMMOibJMdkXwSCyMS05z8mSA4ITHdmsZErYb7cLhtjzm0QQ9tcJ0p8jDawqTVEbO73jsvauiufZCMKB8NZhIN9kBI1jb92jnRIprPhIq5HpqQ5Cik8QycOW3MAeWsoLU69Q1hDwSzidbEaSq5gPY5r,wUVRJDDhfKSUHhNuKnWHZqi0oMTvAwJrC03T5jHXDHKeoT3Co9GQBufHASUqs3ruEQCz4yN3Vl16j6OL4TQTBLVDm8fv2XaNYw4izQGkeGB8kjVg2Pj31WvawaN5CCNpYaVhJSIw0CSY7ocHsJS9w4of1WdZqJcDp3BDURtHFzdDDxD2HOwG1zU0hojqdnBXkLPj2vlH5YwHkXPtVufD6sPA44DhqpjNz2H8UC4E03VTwxUvaaZfUQ479f7tkoou,aCoMeykg5pvPEn0WuClSoTcrTYA0PxWnIQMeMuq9sjaKodlUkUyX27mbYf6Xr10JKoaKsuuI9Eb23vzcy7Q56NDKwLIv1PYtdm4w40tmnrrZ4rgoa6D0oKveHmJd6jRc3ATXQSCQHjk3CmCRPbfqR4kKTUaULyb59VvQiGWhuD0VdDLOQbKGP3wrgNefWsuDMdfmBqIfZHYGSc4FwZSSn2CMyiVS0biQ8UDgCZeMK6hdZq94K4vuYbtUpWDsRjtp,m5mbGpCcjwObAFf0NqDv4kQK1rnm2buajksVSS3HLsXXnHncEdto4Ud000lAG6juse3S1hSI9oE2YifjY8PhenjMHG9SDfdM5VKEMpdHE9ny3RBytqc3HF1lkU7ZozdBzt0uBShh8WcJtE2PpdMGzUsAYuT9POz6RjSkjPlWY5rja6xeDwBcVKxk2Rh8mXdmLQZtd103N7w598v3IPnHGB99g31jmYINELGiTSvvhK1ZWDA4QMGtqopPuztOJQyh,cl9XNGuYU4xoez5HjG1Tvp5hgcVrlocU3JJM4WJE9ZVSLxxlej7CowaQbeYja6rY2WjpRHvqgUfmVztzUX3jfzlhVHVM041kYD1G6ydqeU6smmwzDu3rVEdoDxzJYOkIlpdN1ImPAP9IpahLk3CXKBZxTm3Le6NKImqdZRMG9x25sDiSBplVQhH4Zb6Jnaa4lJWcD1hdcmr1x8AKkmJgsc9TH4hNUF47XpD5RMR3JinwqRACUsgmMnCGxOjOvstq,gSA7Xxb6YPbqzuAuyw7mcEmAjsH2B8gRFo2lSILhAslIVePXerd0wmz9fB2f2XWddvUdHioHUpQeKIiF5EKzCbzLZ5vFeCXZOzbdSLKBLcoXFTd1I2kuGHlo9YB1jbl3KLddLsSyF5T2VfmIUx9A6Qd4ci7lmfVV8Xp6RQL42V6Gx6CEAPBgGD9Sqs0pvWj00eAK1I7tohaeTguZVlDtdGKxreAcRqnMQmhVPEgACJFJh0RTknZslPt0nYoNZiNo,lCUZ7kzjmzWOkFnStAK0gVy3ICmLWN1cWs2GGDXFXk09ixqfQ71JAJqAg87Srhkg8EC5CaPWXS6s8kntYfc1WawZkfLXAYbvNZDCY4aTKjiHeSwhzI6XUyBJbXkJXP6DmGjDhXQmYhbfirPaqftUbtZ1Jf6TeuzPHuoYrJhlomAJK3FNwXs9hljerOSzlZ6Sh4dwn83ey8WoA5MVWJklIfjeuaLGmtLus7cTCUXeILUAAu3SPCmntfEaZAoBIewO,75KmR5y734fdd47Fuh0gk4zG4bpCAjN78HxzxQYsPSVAqHvWGljiEIW7T6XI3z9uz0TukbvIZ1fb0A3D8HpKNTDWAmQ3K9C37NfVcUKJxJ3AxU3UCbkXXBG5qUEmk33ugJ3ieJqM8EqMe3P70uivyVSkHPJ93HidoFp424Hk33S9t78Rz0pr6TE8wQ05vUmUM5jRNPtoraR5nnqEzx5QgjlTnIDwHq8TxL21UM5Gl5QXtn4tfUlE32ugCXEhIFSV,h1LvJGHBqupjbfO4edFr5AD89fi38dJwYm07HZOZiC2vRowWFDZanOVSDFVj9KUmsDmBla0MCGoDby1hoOaIgGmvvpTjwoJl3MUVlxOS63Ra0IfR5WA8HsskJXdje1rNX7Ejnz26hTnEIvbxUdV9TUaVXQFsVT1c8574nlA3R3cjjsG9X1GjWubZtZ8VVE6lpuYunIplySioDdkqfXQAIeOXDodmBWysSuD39h714t0A5bTBzfgL6BHIL1yS7Lep,T7QufPPLCGXYq6cJyQmDfPFwOU9pG3oJ1qAB45StM8rc7wqkbLsT1IXnwsxUmb5TnbmW1dv7WJAYNK8uFVdKrGh6rznE1ApvrFjfjBw0DgpeDB7DZbmpNVv5WHSVRasRtpePVVry81MehC4s6ZMm09YZRwxWWqNWztX1Ht6dmeYqfXjTGhFgRbpqb4JFhSvXq5ta38FUOLXuP5nN7V1nGBH1KedHea3nmzvHT5BLd56xL7YW9tjjEzDPPKWe2wbw,C0QFVSFOyaBeMx7OJ5ZLRZmQLZLW7w9abMmMPIvf3htQ4KaH2IghuVhcPok63EcnpJdvGnuMSsh2B7gwlLYgXguoseVUUGBgsOrh0cb2RoFtXVOStYNEW8hLaw8USrmB90yBxJtYbF2mMbwFNAO3s4l5V8Npy3zFCpkmft5zlNc9F9A0W3maqulX8IcDZD7sKvnQzcvE89xXPMXT7irCoEI9YOST7yM9poQfP7DfyvgDFxvh5xezmdJi26ozwyT1,hEz4aKMBRdLIsMv00V7eoTlwZe6ThIrVI76l0NQU4cqbTLXa3AbANbXo4c5EdOns8pN0sclXqTvIdX9HYh9NhSBVdi8aavPVh1VimpZuoCa0ablQM8Jap9CEKEwLysGwf5596jscfbeDgCFLMOPsBaGQPcvP9qPPdoLhUv6SbTBEU1U4S5lVscbouAl05xevtG5V02fgOxLuFIWSWgmgBEFMa0AEbcHgZKxA6OwPZYrafDrKmyp9JL76WWEhYoH7q15gRKjcfY6o5thrNwzk9VlGmhlk1QItzLvdQwSdbBnT2rAmjNWFskHsBL9TOX3seVmKOghJS79HJO3bQoj7mBK8QNEz83HKGDfXUn5UdEOwNA1Gsm8jZraDkYToWwsXQRoW7Ch5tPisVfHxN0bCHnuZypux3FAUiK5ABxqtGJMKWIO992fhp57UGW4sqeSdMqQa1WzlwpMZbN1h9TQViklJeNIsFDgqrOpEmySZ2tfo5LCtDlEU9BjmA1lqGnrdNxs187UM2hY1LRESS2JkFwKdBXwETWSjnyacuYuB0QpC8BXC4GJYxQSP5UU7nv916rUOUBMYTokJLxtEbQiBnClodPcqYAHKbXGs171TkV9gczwvxMRYRcN9mtHwQwqd4J9ioUDUt85Hydl7CY8EJoxH1DjLFHrPw7OhjOruMzi3m64YJMaSwjbLpnxAkVy0wgheLTeTQmXcUvgduz5U2fAa58RkwizOQe6S76DW2h3m6C68WXLI9nwEOJEmqp1R,QDUkxG7u5KC9FOvCEGUq5B1mDi8iLA2qG8jhRIqOs02AKAYkBNp7f1eWAvf8oL66vzLLusJvL2PHVhN0usAhzjR8uSWUsF8W7HW4b1vZ4I7uDsnPY00a6vOavLeDGwDgzIxTVxoGDxY0yauZ9Q2dj1mh8qj7Ac6uEMFl6wRuhYbZojgiVIRAubxLL8CaCXc20xpDP4kwyoq4nWzw7KFOIxLvCaGNiyAa0SkSjMK9tCcXmoLvz9rG5PrbAQPzZx2a,ngQgpjucVFtmdIleIujJiwOfDnjbT4IiMuNpDhw8SoF7vYO7cmgeh2heEjF8DCb8dUi6X2VJdiivZvtM2cY9i8UzfHw6XBExzqezoYDCMayNz7SwfMRBxdzBgPYQzkfPfM9WkEuHVlxB5KYzkyuoBLWyv3ULtV0AZHnrait6HgkrPbGYqicm9S0RWD9tjLzTpYEd57nJ7vcYOpnC2EsdsLmmr9zjKJ7dKTqWWV79UIa0MZEGnJihgRD9MqUs6zYR,uftiByMpEA241F9R6RBhzl2pDNzbspxgLaFa6oI1dR3vBWdlpTJEk1wW6CZBaXJL8POYkAVHMxVwDxt5MdFpMTy9bK61K8tmnu06Fu59Py5TkAUGrEL4MN5wh8qWTVdjsVo9jDdmmLISl9Ntoquoxc8ZTS6vwTkhvTs3JT8gUv1y3rPJDlyLcf6T1EgjemM6uKVd2dYxwduqA0Hp9dCoHSBi363zKO6K77hz55ShTKF6zCtUZJKOclvOreY0h1ks,P9FGVNTJQUt2aoN9Mu0bUXHcb3zQOUAY31bcV67eyLaZmpE7UyDaWEP4FtiEnDEy7FML0Jflq8WABl'
2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:12 [6, 11]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:26A39883-A498-46D9-BCE1-537D2CD964F5
,[ThaliCore] Session.session(_:peer:didChange:) peer:26A39883-A498-46D9-BCE1-537D2CD964F5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26A39883-A498-46D9-BCE1-537D2CD964F5
[ThaliCore] Session.startOutputStream(with:) peer:26A39883-A498-46D9-BCE1-537D2CD964F5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [6, 11, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (2403 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (4451 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (2403 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (5617 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received (931 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [6, 11]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 11:03:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:03:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F4F5F622-E47B-4CE5-B8AE-21666B67C798
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:FA2EE142-1A99-4149-AB82-FAA6044948AC
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59633
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: 0)
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:26A39883-A498-46D9-BCE1-537D2CD964F5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:26A39883-A498-46D9-BCE1-537D2CD964F5
[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nXM9BSTDIZqdWd6huUXZsh17hdWdki5z","error":"Session disconnected","portNumber":null}'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FA2EE142-1A99-4149-AB82-FAA6044948AC","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FA2EE142-1A99-4149-AB82-FAA6044948AC","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4448EFB5-325D-4402-9F4B-B3F19AE2501B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:26A39883-A498-46D9-BCE1-537D2CD964F5
,[ThaliCore] Session.deinit peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0157875A-30BC-40AC-9CAF-CCD46A387371", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0157875A-30BC-40AC-9CAF-CCD46A387371
2017-07-24 1,1:03:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:03:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AC10BBBC-B5AB-467D-B9B2-E9E6F4AB0295
[ThaliCore] Browser.startListening
2017-07,-,24 11:03:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:03:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: 0)
[ThaliCore] AdvertiserManager,.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0157875A-30BC-40AC-9CAF-CCD46A387371
2017-07-24 11:03:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
201,7-07-24 11:03:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret",:null,"networkType":null}})'
2017-07-24 11:03:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopList,e,ning()
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
2017-07-24 11:03:51 -, DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 test stop ,worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-24 11:03:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:544C6329-1885-461A-91DF-A80CE9312F3A
[ThaliCore] Browser.startListening
ok 107 discoveryActive should be false
ok 108 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2278F795-983B-4A6D-A9FD-F2F7F8C127F1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2278F795-983B-4A6D-A9FD-F2F7,F8C127F1
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 111 discoveryActive should be false
ok 112 advertisingActive sh,ould be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2278F795-983B-4A6D-A9FD-F2F7F8C127F1
ok 113 discoveryActive should be false
ok 114 advertisingActive should be true
ok 115 Can call startList,e,ningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-24 11:03:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-24 11:03:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:56 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-24 11:03:56 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-24 11:03:57 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-24 11:03:57 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-24 11:03:58 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:4a18949d-2f34-430b-84be-5b41cf818683 error: startListeningNotActive
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JpnaAMxzFQp6AOZOcXg6G7U3XUmCOwEX","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 129 Should only get called after multiConnect returned
ok 130 SyncValue matches
ok 131 Got right error
ok 132 listeningPort ,is null
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4a18949d-2f34-430b-84be-5b41cf818683","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:03:58 - DEBUG t,haliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4a18949d-2f34-430b-84be-5,b,41cf818683","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:03:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:03:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D2B1EC7E-42AF-4887-9628-885444ACEC40
[ThaliCore] Browser.startListening
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 No error on starting
ok 134 Got null as expected
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper:, 'multiConnectResolved: {"syncValue":"ar47MX4qjgm8R1i7mbJIpNQf6nBICbVU","error":"Illegal peerID","portNumber":null}'
ok 135 Should only get called after multiConnect returned
ok 136 SyncValue matches
ok 137 Got right error
ok 138 listeningPort is null,
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"BD9D579D-72C6-46B0-B79B-4E6BA3F58861","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"BD9D579D-72C6-46B0-B79B-4E6BA3F58861","generation":0}'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"12089FF0-3ECC-40A2-A184-6C264C0E4B6C","generation":0}]'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"12089FF0-3ECC-40A2-A184-6C264C0E4B6C","generation":0}'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-24 11:03:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:03:59 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:440D286F-25E4-4462-B951-C061353AE99C
[ThaliCore] Browser.startListening
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 139 No error on starting
,ok 140 Got right error
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"BD9D579D-72C6-46B0-B79B-4E6BA3F58861","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"BD9D579D-72C6-46B0-B79B-4E6BA3F58861","generation":0}'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"12089FF0-3ECC-40A2-A184-6C264C0E4B6C","generation":0}]'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"12089FF0-3ECC-40A2-A184-6C264C0E4B6C","generation":0}'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 11:04:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:04:00 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:3e4f402b-6dae-403d-ae1a-8701d3d3e26c
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:04:00 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "63BAE976-BEB5-4F9C-9652-5FC045F4AD23", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:63BAE976-BEB5-4F9C-9652-5FC045F4AD23
2017-07-24 11:04:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:01, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 11:04:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:72295678-8011-4539-889C-0FE1169457D4
[ThaliCore] Browser.startListening
2017-07-24 11:04:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-24 11:04:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
2017-07-24 11:04:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BD9D579D-72C6-46B0-B79B-4E6BA3F58861","generation":0}'
2017-07-24 11:04:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BD9D579D-72C6-46B0-B79B-4E6BA3F58861, (syncValue: BY1mZPQeWTrEhmjEme6o6AOPOv7rd2zS)'
2017-07-24 11:04:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F,58861", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C",, generation: 0)
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:04:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"12089FF0-3ECC-40A2-A184-6C264C0E4B6C","generation":0}'
2017-07-24 11:04:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
2017-07-24 11:04:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5837337D-36B1-4BEE-A7F0-8A59B6E8E759","generation":0}'
2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:02 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
2017-07-24 11:04:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C923BA5-B7BD-4950-A19A-1BFD7C7541D1","generation":0}'
2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:02 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:63BAE976-BEB5-4F9C-9652-5FC045F4AD23:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "63BAE976-BEB5-4F9C-9652-5FC045F4AD23", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,D9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,D9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BD,9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BD9D579D,-72C6-46B0-B79B-4E6BA3F58861 error: max retries exceeded
2017-07-24 11:04:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BY1mZPQeWTrEhmjEme6o6AOPOv7rd2zS","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:04:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BY1mZPQeWTrEhmjEme6o6AOPOv7rd2zS', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:04:12 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"BD9D579D-72C6-46B0-B79B-4E6BA3F58861","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:04:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-24 11:04:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BD9D579D-72C6-46B0-B79B-4E6BA3F58861","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 11:04:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:04:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 12089FF0-3ECC-40A2-A184-6C264C0E4B6C (syncValue: PIruwht,XY2JzTSDBhYN0wgabhaTx9jK9)'
2017-07-24 11:04:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:12089FF0-3ECC,-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:04:12 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-07-24 11:04:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:12,089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,2089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:12,089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,2089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:12,089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,2089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C error: max retries exceeded
,2017-07-24 11:04:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PIruwhtXY2JzTSDBhYN0wgabhaTx9jK9","error":"Connection could not be established","portNumber":null}'
,2017-07-24 11:04:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PIruwhtXY2JzTSDBhYN0wgabhaTx9jK9', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 11:04:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"12089FF0-3ECC-40A2-A184-6C264C0E4B6C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"12089FF0-3ECC-40A2-A184-6C264C0E4B6C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:23 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-24 11:04:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5837337D-36B1-4BEE-A7F0-8A59B6E8E759 (syncValue: 3R6w3tCiCo4rsUOTLejemeUVNycpbnot)'
,2017-07-24 11:04:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:04:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59659
2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3R6w3tCiCo4rsUOTLejemeUVNycpbnot",,"error":null,"portNumber":59659}'
2017-07-24 11:04:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3R6w3tCiCo4rsUOTLejemeUVNycpbnot', error: 'null', listeningPort: '59659''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
ok 145 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) found active relay
2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2COp6HUmcfUfy1Fqdjfpvu6haMI6xSj,4","error":null,"portNumber":59659}'
ok 146 No error
ok 147 Ports equal
,ok 148 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) found active relay
2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'multiConn,ectResolved: {"syncValue":"NEHi1Kdt2CmxVEWd6Nl3nqjM5rZRjEMI","error":null,"portNumber":59659}'
ok 149 No error
ok 150 Ports equal
# teardown
,2017-07-24 11:04:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:04:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:63BAE976-BEB5-4F9C-9652-5FC045F4AD23
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:04:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59659
[ThaliCore] Session.disconnect() p,eer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-24 11:04:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:04:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-24 11:04:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:04:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-24 11:04:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-24 11:04:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:04:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-24 11:04:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:04:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-24 11:04:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:04:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'listening 59662'
ok 151 Should throw
,# teardown
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'listening 59664'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:31 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 11:04:31 - DEBUG createNativeListener: 'listening 59667'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 11:04:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:31 - DEBUG createNativeListener: 'Native Server - close'
2017-07-24 11:04:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 11:04:32 - DEBUG createNativeListener: 'listening 59671'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 11:04:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - ,0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
ok 158 Send/recvd #1 should be same
ok 159 Send/recvd #2 should be equal length
ok 160 Send/recvd #2 should be same
ok 161 Should be exactly 2 client sockets
,# teardown
,2017-07-24 11:04:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:32 - DEBUG createNativeListener: 'Native Server - close'
2017-07-24 11:04:32, - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-24 11:04:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-24 11:04:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
2017-07-24 11:04:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-07-24 11:04:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection, to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'listening 59676'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 11:04:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
,ok 163 incoming remains open
,# teardown
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 11:04:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'listening 59680'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 164 we should not have gotten an error
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 11:04:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'listening 59684'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-07-24 11:04:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-24 11:04:33, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 11:04:33 - DEBUG createNativeListener: 'listening 59688'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 170 we should not have gotten an error
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
2017-07-24 11:04:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-24 11:04:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 172 native server is nulled out
ok 173 native server should be cl,osed
ok 174 incoming has been removed
ok 175 Incoming should be done
ok 176 The mux object should be closed
ok 177 The mux stream should be closed
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 11:04:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'listening 59692'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-24 11:04:34 - DEBUG createNativeListener: 'incom,ing - incoming Android TCP/IP client connection <-> Mux - 1'
2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux ,- 2'
2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-24 11:04:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 11:04:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-24 11:04:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 11:04:35 - DEBUG createNativeListener: 'listening 59744'
,2017-07-24 11:04:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 11:04:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 181 we should not have gotten an error
,2017-07-24 11:04:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
2017-07-24 11:04:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-24 11:04:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 183 server should be fine
ok 184 server should be open
ok 185 incoming has been removed
ok 186 The mux object should be clos,ed
ok 187 The mux stream should be closed
2017-07-24 11:04:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 11:04:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'listening 59748'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 11:04:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:36 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 11:04:37 - DEBUG createNativeListener: 'listening 59751'
,ok 198 port must be in range
,# teardown
,2017-07-24 11:04:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'listening 59752'
ok 199 second start should return same port
,# teardown
,2017-07-24 11:04:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'listening 59754'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 11:04:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 200 we should be connected
2017-07-24 11:04:37 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 201 now we are disconnected
,2017-07-24 11:04:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-24 11:04:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-24 11:04:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 202 Passed bogus id
2017-07-24 11:04:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
ok 203 Passed good id but bogus port
2017-07-24 11:04:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 204 Passed right context
ok 205 Right server
ok 206 No error should be set
ok 207 Ret,ry should be false
ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 59756
,ok 209 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:04:38 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:04:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:04:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:04:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:750E6DFD-0414-4611-9C4A-7D7FD6C84C77
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:48EDAA19-7445-4E6B-ABBA-BC18A1C,615E4
[ThaliCore] Browser.startListening
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:04:38 - INFO thaliMobile: 'Received state ({"discove,r,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:38 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
2017-07-24 11:04:38 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"5837337D-36B1-4BEE-A7F0-8A59B6E8E759","generation":0}'
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5837337D-36B1-4BEE-A7F0-8A59B6E8E759 (syncValue: sVEKeBS6TrilNBY5miXfhybDMQFRvvUa)'
2017-07-24 11:04:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C923BA5-B7BD-4950-A19A-1BFD7C7541D1","generation":0}'
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"91033B82-7A22-4EE1-8C6F-0D07A8443692","generation":0}'
2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E","generation":0}'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:58,37337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:58,37337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:58,37337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:04:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sVEKeBS6TrilNBY5miXfhybDMQFRvvUa","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:04:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sVEKeBS6TrilNBY5miXfhybDMQFRvvUa', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:04:46 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"5837337D-36B1-4BEE-A7F0-8A59B6E8E759","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:04:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 11:04:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5837337D-36B1-4BEE-A7F0-8A59B6E8E759","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-24 11:04:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 11:04:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 91033B82-7A22-4EE1-8C6F-0D07A8443692 (syncValue: HM1enFZiN0Dqtjp1q0wRqy85zENnXpfM)'
2017-07-24 11:04:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:91033B82-7A22-4EE1-8C6F-0D07A,8443692:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:04:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
2017-07-24 11:04:47 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5837337D-36B1-4BEE-A7F0-8A59B6E8E759","generation":0}'
2017-07-24 11:04:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:47 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 11:04:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1
[ThaliCore] Advertiser: session connected Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59768
2017-07-24 11:04:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HM1enFZiN0Dqtjp1q0wRqy85zENnXpfM",,"error":null,"portNumber":59768}'
2017-07-24 11:04:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HM1enFZiN0Dqtjp1q0wRqy85zENnXpfM', error: 'null', listeningPort: '59768''
,ok 212 should be equal
2017-07-24 11:04:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E (syncValue: eZ942b20RBWJSsBzoOOiBWNLdlTsHJHe)'
2017-07-24 11:04:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:04:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4
[ThaliCore] Advertiser: session connected Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1
,[ThaliCore] Session.session(_:peer:didChange:) peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59772
,2017-07-24 11:04:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eZ942b20RBWJSsBzoOOiBWNLdlTsHJHe","error":null,"portNumber":59772}'
,2017-07-24 11:04:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eZ942b20RBWJSsBzoOOiBWNLdlTsHJHe', error: 'null', listeningPort: '59772''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4
,ok 213 should be equal
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4 state: connecting -> connected
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:04:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,11:04:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 11:04:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:750E6DFD-0414-4611-9C4A-7,D7FD6C84C77
2017-07-24 11:04:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:04:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:91033B82-7A22-4EE1-8C6F-0D07A8443692
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59768
[ThaliCore] Session.disconnect() peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:59772
[ThaliCore] Session.disconnect() peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1 state: connected -> notConnected
[ThaliCore] Adv,ertiser: session notConnected Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.dis,connectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4
,[ThaliCore] Session.deinit peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E
,2017-07-24 11:04:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eZ942b20RBWJSsBzoOOiBWNLdlTsHJHe","error":"Session disconnected","portNumber":null}'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4
,[ThaliCore] Session.deinit peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 59774
,ok 214 should be equal
ok 215 should be equal
ok 216 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:04:56 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:04:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:04:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:04:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C1DE2F08-A697-4531-80C7-AC50F60F4088
2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 11:04:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EC47B1DF-2B3B-475B-999E-F4C699022015
[ThaliCore] Browser.startListening
2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-24 11:04:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
2017-07-24 11:04:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"91033B82-7A22-4EE1-8C6F-0D07A8443692","generation":0}'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 91033B82-7A22-4EE1-8C6F-0D07A8443692, (syncValue: sCVPoP3J7wiuHDZwQFGBsErCpBCxxPsr)'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A84,43692", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E","generation":0}'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
2017-07-24 11:04:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","generation":0}'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generatio,n,":0}'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-0,7-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91,033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,1033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91,033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,1033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91,033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,1033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:91033B82,-7A22-4EE1-8C6F-0D07A8443692 error: max retries exceeded
2017-07-24 11:05:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sCVPoP3J7wiuHDZwQFGBsErCpBCxxPsr","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:05:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sCVPoP3J7wiuHDZwQFGBsErCpBCxxPsr', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:05:09 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"91033B82-7A22-4EE1-8C6F-0D07A8443692","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:05:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-24 11:05:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"91033B82-7A22-4EE1-8C6F-0D07A8443692","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 11:05:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:05:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:05:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D2BCE3C4-528F-472A-A98F-01BEF298D54C (syncValue: 9HMhF5E,QDY8HAR8th4AsCkPP9KeWyDDg)'
2017-07-24 11:05:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D2BCE3C4-528F,-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:05:09 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t!'
2017-07-24 11:05:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59792
2017-07-24 11:05:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9HMhF5EQDY8HAR8th4AsCkPP9KeWyDDg",,"error":null,"portNumber":59792}'
2017-07-24 11:05:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9HMhF5EQDY8HAR8th4AsCkPP9KeWyDDg', error: 'null', listeningPort: '59792''
,ok 219 should be equal
ok 220 should be equal
ok 221 should be equal
2017-07-24 11:05:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 07DC7689-843B-41FF-8F84-A0AFB584488F (syncValue: L0fdOeinqYu6S63wqz7VwPIaltq4E1iO)'
2017-07-24 11:05:,12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0) creating a new relay
[ThaliCore] Browser.i,nviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] Browser,Relay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7
[ThaliCore] Advertiser: session connected Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59798
2017-07-24 11:05:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"L0fdOeinqYu6S63wqz7VwPIaltq4E1iO",,"error":null,"portNumber":59798}'
2017-07-24 11:05:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'L0fdOeinqYu6S63wqz7VwPIaltq4E1iO', error: 'null', listeningPort: '59798''
,ok 222 should be equal
ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7
,[ThaliCore] Session.session(_:peer:didChange:) peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33
[ThaliCore] Advertiser: session connected Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33
,[ThaliCore] Session.session(_:peer:didChange:) peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,11:05:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C1DE2F08-A697-4531-80C7-A,C50F60F4088
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59792
[ThaliCore] Sessi,on.disconnect() peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7 ,state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
,[ThaliCore] Session.deinit peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:07DC7689-843B-41FF-8F84-A0AFB584488F
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59798
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
,2017-07-24 11:05:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"L0fdOeinqYu6S63wqz7VwPIaltq4E1iO","error":"Session disconnected","portNumber":null}'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33
[ThaliCore] Session.deinit peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:24 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:25 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'listening 59802'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 231 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'listening 59803'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:455D4BEC-EC2F-40AA-A52A-24E2AAD6E0B7
[ThaliCore] Browser.st,artListening
2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 232 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertis,i,ngActive":false}'
2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router,":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 still no errors
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}]'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","generation":0}]'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","generation":0}'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 234 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'listening 59804'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BDB51668-7C31-4CA7-8D7B-458A535F5A8C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BDB51668-7C31-4CA7-8D7B-458A535F5A8C
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BDB51668-7C31-4CA7-8D7B-458A535F5A8C", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:BDB51668-7C31-4CA7-8D7B-458A535F5A8C
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BDB51668-7C31-4CA7-8D7B-458A535F5A8C
,[ThaliCore] Advertiser.stopAdvertising() peerID:BDB51668-7C31-4CA7-8D7B-458A535F5A8C
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 237 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'listening 59807'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 238 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 239 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 241 network status should have certain non-empty properties
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:27 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-24 11:05:27 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 243 specific error expected
,# teardown
,ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'listening 59808'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FBA8C103-B82E-4DF2-93F0-D33930A31A8B
[ThaliCore] Browser.startListening
2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D8B4BFEF-70D5-487C-A1FC-CAD02253D1D8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,D8B4BFEF-70D5-487C-A1FC-CAD02253D1D8
2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:28 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 all connection succeed
# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D8B4BFEF-70D5-487C-A1FC-CAD02253D1D8
2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:28 - DEBUG thaliMobi,leNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'listening 59811'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B79BA3D6-63F2-4B76-A95B-F2098531D713
[ThaliCore] Browser.st,artListening
2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "027335A0-DB7A-4638-BF03-DC031BADDEE5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,027335A0-DB7A-4638-BF03-DC031BADDEE5
2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 247 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:027335A0-DB7A-4638-BF03-DC031BADDEE5
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 248 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'listening 59813'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F45F6F36-8433-4168-93C6-B1F4825456EF
[ThaliCore] Browser.st,artListening
2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E5D64EB1-EB82-4D9E-B851-FF290B7C815B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,E5D64EB1-EB82-4D9E-B851-FF290B7C815B
2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:05:29 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:29 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E5D64EB1-EB82-4D9E-B851-FF290B7C815B
2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrap,per: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"lis,t,ening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 11:05:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 249 is stopped after calling stop
,ok 250 connection should fail after stopping
,# teardown
,ok 251 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-24 11:05:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 253 error description matches
,# teardown
,ok 254 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-24 11:05:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 256 error description matches
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 258 IMPLEMENT ME!!!!!!
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-24 11:05:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-24 11:05:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-24 11:05:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-24 11:05:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 264 NOT IMPLEMENTED # SKIP
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-24 11:05:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-24 11:05:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-24 11:05:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 268 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-24 11:05:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 269 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:34 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:34 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 59816'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8A9B58EA-D15C-490D-82B5-41E3C6E115CB
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,2017-07-24 11:05:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 59817'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "18045CDE-6BB0-479D-A85C-C3C52A9935F1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:18045CDE-6BB0-479D-A85C-C3C52A9935F1
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:18045CDE-6BB0-479D-A85C-C3C52A9935F1
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 276 discoveryActive matches
,ok 277 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 59819'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 59820'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1BD54B70-4DBB-4C40-B9EE-50A7F1673B08
[ThaliCore] Browser.startListening
2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,BF26BDFD-8E8A-4A40-9359-CD7F3626111F
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
2017-07-24 11:05:35 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}]'
2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}'
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:05:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 279 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:86C127E7-58B5-42BA-8ABA-1587918D0BF8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0)
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","generation":0}]'
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","generation":0}'
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BF26BDFD-8E8A-4A40-9359-CD7F3626111F
2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 11:05:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:05:36 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:05:36 - DEBUG makeIntoCloseA,llServer: 'closeAll called on server'
ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingA,ctive":false}'
2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSta,t,eUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'listening 59822'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:17F0E4CA-AFA5-42FB-BD68-6F50E15C1E22
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:86C127E7-58B5-42BA-8ABA-1587918D0BF8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0)
2017-07-24 11:05:37 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","generation":0}]'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
2017-07-24 11:05:37 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF26,BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"86C127E7-58B5-,42BA-8ABA-1587918D0BF8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 86C127E7-58B5-42BA-8ABA-1587918D0BF8 (syncValue: dyz82JfkOPIRbNQ8Zny6a4AoOxKBwvd8)'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:86C127E7-58B5-42BA-8ABA-1587918D0BF8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}]'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}]'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:86C127E7-58B5-42BA-8ABA-1587918D0BF8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0)
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","generation":0}]'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserManager.foundPeerHandle,r peer:Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":false,"generation":n,u,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
ll,"portNumber":null}'
2017-,07-24 11:05:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 11:05:37 - DE,BUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}]'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer a,vailability changed event with {"peerAvailable":true,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032,F5F447","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
2017-07-24 11:05:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"687F0B9,1-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","generation":0}]'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","generation":0}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:86C127E7-58B5-42BA-8ABA-1587918D0BF8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:86,C127E7-58B5-42BA-8ABA-1587918D0BF8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,6C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:05:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dyz82JfkOPIRbNQ8Zny6a4AoOxKBwvd8","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:05:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dyz82JfkOPIRbNQ8Zny6a4AoOxKBwvd8', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:05:40 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:05:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:05:40 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:05:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:86C127E7-58B5-42BA-8ABA-1587918D0BF8
2017-07-24 11:05:40 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-24 11:05:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 21C76FB1-27B2-410D-9F47-FB2CAE986934 (syncValue: zAyI4K2CxBVcZIaL00uffOWcMfqCE4Wj)'
2017-07-24 11:05:40 - DEBUG thaliMobileNativeTestUt,i,ls: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:s,essionNotConnected:) Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] BrowserRelay.init(session:generation:creat,eVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:86C127E7-58B5-42BA-8ABA-1587918D0BF8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
2017-07-24 11:05:41 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}]'
2017-07-24 11:05:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}'
,2017-07-24 11:05:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
2017-07-24 11:05:42 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}]'
2017-07-24 11:05:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}'
,2017-07-24 11:05:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:05:42 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:21,C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,1C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 11:05:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zAyI4K2CxBVcZIaL00uffOWcMfqCE4Wj","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 11:05:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zAyI4K2CxBVcZIaL00uffOWcMfqCE4Wj', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 11:05:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:21C76FB1-27B2-410D-9F47-FB2CAE986934
,2017-07-24 11:05:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 11:05:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BF26BDFD-8E8A-4A40-9359-CD7F3626111F (syncValue: Gv92YYuA2vcLcfEoKNwUQxhjlfvQDlug)'
,2017-07-24 11:05:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,F26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D15069AD-B38D-4EF4-A83B-D237CEC6E2FD
[ThaliCore] Advertiser: session connected Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D15069AD-B38D-4EF4-A83B-D237CEC6E2FD state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,F26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
2017-07-24 11:05:49 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}]'
2017-07-24 11:05:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}'
,2017-07-24 11:05:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:05:49 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D15069AD-B38D-4EF4-A83B-D237CEC6E2FD
,[ThaliCore] Session.session(_:peer:didChange:) peer:D15069AD-B38D-4EF4-A83B-D237CEC6E2FD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D15069AD-B38D-4EF4-A83B-D237CEC6E2FD
[ThaliCore] Session.startOutputStream(with:) peer:D15069AD-B38D-4EF4-A83B-D237CEC6E2FD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [6, 11, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,F26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BF26BDFD,-8E8A-4A40-9359-CD7F3626111F error: max retries exceeded
[ThaliCore] Session.deinit peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 11:05:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Gv,92YYuA2vcLcfEoKNwUQxhjlfvQDlug","error":"Connection could not be established","portNumber":null}'
2017-07-24 11:05:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Gv92YYuA2vcLcfEoKNwUQxhjlfvQDlug', error: 'Connection could n,o,t be established', listeningPort: '%s''
2017-07-24 11:05:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":false,"portNumber":null,"recreated":true},'
2017-07-24 11:05:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:05:53 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 11:05:53 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-24 11:05:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 11:05:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-24 11:05:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:05:53 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 687F0B91-75C2-4D17-A950-AE8032F5F447 (syncValue: u09kv3NZCYki1pALtaZuOfCanImhiAyd)'
2017-07-24 11:05:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "687F0B91-75C2-4D17-A950-A,E8032F5F447", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(wit,h:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59851
2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"u09kv3NZCYki1pALtaZuOfCanImhiAyd",,"error":null,"portNumber":59851}'
2017-07-24 11:05:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'u09kv3NZCYki1pALtaZuOfCanImhiAyd', error: 'null', listeningPort: '59851''
,2017-07-24 11:05:56 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [6, 11, 14, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:05:56 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:05:56 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
,ok 282 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [6, 11, 15]
,ok 283 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:687F0B91-75C2-4D17-A950-AE8032F5F447
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59851
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:15 [6, 11]
,[ThaliCore] Session.disconnect() peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"u09kv3NZCYki1pALtaZuOfCanImhiAyd","error":"Session disconnected","portNumber":null}'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D15069AD-B38D-4EF4-A83B-D237CEC6E2FD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D15069AD-B38D-4EF4-A83B-D237CEC6E2FD
,[ThaliCore] Session.deinit peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserRelay.deinit
,# can still do HTTP requests between peers with coordinator
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'listening 59853'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D49DF1D2-7638-45E5-924E-9788D599707C
[ThaliCore] Browser.st,artListening
2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:57 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,BC19DA9F-A334-4CA1-8FCD-469184F8E157
2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:05:57 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:57 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.deinit peer:D15069AD-B38D-4EF4-A83B-D237CEC6E2FD
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","generation":0}]'
2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","generation":0}'
2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A24BFF38-9898-41C6-,87EB-9ADA562612FE","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:05:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"generation":0,"portNumber":nu,l,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
l}'
2017-07-24 11:05:58 - DE,BUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A24BFF38-9898-41C6-87EB-9ADA562612FE (syncValue: gRul3psIPKDiIWrC1i29j1kHjQ8IVkM1)'
2017-07-24 11:05:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager,.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA,562612FE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:s,ocketDisconnected:stoppedListening:)
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}]'
2017-07-24 11:05:58 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
2017-07-24 11:05:58 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","generation":0}]'
2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
2017-07-24 11:05:58 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:05:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 11:05:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"076336D,2-906B-45A8-9499-6D7BDC53DCA7","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0)
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","generation":0}]'
2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","generation":0}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,4BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,4BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
2017-07-24 11:06:05 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","generation":0}]'
2017-07-24 11:06:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","generation":0}'
,2017-07-24 11:06:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:06:05 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,4BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:06:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gRul3psIPKDiIWrC1i29j1kHjQ8IVkM1","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:06:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gRul3psIPKDiIWrC1i29j1kHjQ8IVkM1', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:06:06 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:06:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:06:06 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:06:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:A24BFF38-9898-41C6-87EB-9ADA562612FE
2017-07-24 11:06:06 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-24 11:06:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 687F0B91-75C2-4D17-A950-AE8032F5F447 (syncValue: kd1CyP8AvtoJUxD3KNeuIs8Zx9OayCQZ)'
2017-07-24 11:06:06 - DEBUG thaliMobileNativeTestUt,i,ls: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:s,essionNotConnected:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.init(session:generation:creat,eVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B1A72C93-840E-4716-A305-79B57337FFD2
[ThaliCore] Advertiser: session connected Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B1A72C93-840E-4716-A305-79B57337FFD2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,7F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
2017-07-24 11:06:11 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}]'
2017-07-24 11:06:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}'
,2017-07-24 11:06:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:06:11 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,7F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:06:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kd1CyP8AvtoJUxD3KNeuIs8Zx9OayCQZ","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:06:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kd1CyP8AvtoJUxD3KNeuIs8Zx9OayCQZ', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:06:11 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:06:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:06:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:06:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:687F0B91-75C2-4D17-A950-AE8032F5F447
2017-07-24 11:06:11 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-24 11:06:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 076336D2-906B-45A8-9499-6D7BDC53DCA7 (syncValue: 6ME0VtBU2A6ONYzLFpFkHfUJUZXfh9WN)'
2017-07-24 11:06:11 - DEBUG thaliMobileNativeTestUt,ils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:,sessionNotConnected:) Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B1A72C93-840E-4716-A305-79B57337FFD2
,[ThaliCore] Session.session(_:peer:didChange:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0 state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:B1A72C93-840E-4716-A305-79B57337FFD2 state: connecting -> connected
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B1A72C93-840E-4716-A305-79B57337FFD2
[ThaliCore] Session.startOutputStream(with:) peer:B1A72C93-840E-4716-A305-79B57337FFD2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [6, 11, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59870
2017-07-24 11:06:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6ME0VtBU2A6ONYzLFpFkHfUJUZXfh9WN",,"error":null,"portNumber":59870}'
2017-07-24 11:06:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6ME0VtBU2A6ONYzLFpFkHfUJUZXfh9WN', error: 'null', listeningPort: '59870''
,2017-07-24 11:06:14 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [6, 11, 16, 17]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:06:14 - DEBUG testUtils: 'Got response data'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6C097E42-E518-480B-9D1F-E821DF619B8A
[ThaliCore] Advertiser: session connected Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184,F8E157", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6C097E42-E518-480B-9D1F-E821DF619B8A state: notConnected -> connecting
2017-07-24 11:06:14 - DEBUG testUtils: 'Got end'
ok 284 response body should match testData
ok 285 must be started
# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6C097E42-E518-480B-9D1F-E821DF619B8A
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C097E42-E518-480B-9D1F-E821DF619B8A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6C097E42-E518-480B-9D1F-E821DF619B8A
[ThaliCore] Session.startOutputStream(with:) peer:6C097E42-E518-480B-9D1F-E821DF619B8A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [6, 11, 16, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BC19DA9F-A334-4CA1-8FCD-469184F8E157
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 11:06:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-24 11:06:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:18 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brow,serManager.disconnect peer:076336D2-906B-45A8-9499-6D7BDC53DCA7
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59870
[ThaliCore] VirtualSocket.closeStreams() vsID:17,
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPL,istener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Err,or Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] TCPClient.socketDidDisc,onnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Tha,liCore] Session.disconnect() peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:17 [6, 11, 16, 18]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] Session.deinit peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
,[ThaliCore] TCPListener.deinit
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to n,ative'
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[Thal,iCore] BrowserRelay.deinit
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] Session.session(_:peer:didChange:) peer:6C097E42-E518-480B-9D1F-E821DF619B8A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] AdvertiserRelay.disconnectNonTCP,Session()
[ThaliCore] Session.disconnect() peer:6C097E42-E518-480B-9D1F-E821DF619B8A
[ThaliCore] VirtualSocket.deinit vsID:16 [6, 11, 18]
[ThaliCore] Session.deinit peer:6C097E42-E518-480B-9D1F-E821DF619B8A
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] TCPClient.deinit
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [6, 11]
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:B1A72C93-840E-4716-A305-79B57337FFD2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
,# calls correct starts when network changes
,2017-07-24 11:06:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:19 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:06:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 59873'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F7A2A256-543A-410A-961E-7BCC035FB0C7
[ThaliCore] Browser.st,artListening
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:06:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,10087D13-05EC-4EC5-A858-75B42091AB0B
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:06:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
2017-07-24 11:06:20 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","generation":0}]'
2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0)
2017-07-24 11:06:20 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 076336D2-906B-45A8-9499-6D7BDC53DCA7 (syncValue: VOPx1ooGM1FgfY8,m8WdiWsUo1RvxJEAt)'
2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0) crea,t,ing a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:076336D2-906B-45A8-94,99-6D7BDC53DCA7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChang,ed event from native layer [{"peerAvailable":true,"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","generation":0}]'
2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIde,ntifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","generation":0}'
2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":true,"generation":0,,",portNumber":null}'
2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
2017-07-24 11:06:20 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}]'
2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:06:20 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9D2D069F-2F60-447B-B8BA-60B087ACB18C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D2D069F-2F60-447B-B8BA-60B087ACB18C", generation: 0)
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","generation":0}]'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","generation":0}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:07,6336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,76336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:07,6336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,76336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:07,6336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,76336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
2017-07-24 11:06:28 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","generation":0}]'
2017-07-24 11:06:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","generation":0}'
,2017-07-24 11:06:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:06:28 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:07,6336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:076336D2,-906B-45A8-9499-6D7BDC53DCA7 error: max retries exceeded
2017-07-24 11:06:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VOPx1ooGM1FgfY8m8WdiWsUo1RvxJEAt","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:06:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VOPx1ooGM1FgfY8m8WdiWsUo1RvxJEAt', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:06:30 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:06:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {,"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:06:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DC,A7","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:06:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","peerAvailable":true,,"portNumber":null,"recreated":true}'
2017-07-24 11:06:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.dis,connect peer:076336D2-906B-45A8-9499-6D7BDC53DCA7
2017-07-24 11:06:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EE5E1924-9B07,-4D31-896D-0D8D34B5D9C9
[ThaliCore] Advertiser: session connected Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EE5E1924-9B07-4D31-896D-0D8D34B5D9C9 state: notConnected -> connecting
2017-07-24 11:06:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 951E5565-7CD1-4438-B15D-EB97D09CF081 (syncValue: 2jPrtKdGFG7gS4pUWq2M9Nh,31f69hkrC)'
2017-07-24 11:06:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EE5E1924-9B07-4D31-896D-0D8D34B5D9C9
,[ThaliCore] Session.session(_:peer:didChange:) peer:EE5E1924-9B07-4D31-896D-0D8D34B5D9C9 state: connecting -> connected
[ThaliCore] Session.session(_:peer:didChange:) peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0 state: notConnected -> notConnected
[ThaliC,ore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "951E5565-7CD1-4438-B15D-,EB97D09CF081", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessi,onNotConnected:) Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0
[ThaliCore] BrowserRelay.init(session:generation:createVi,r,tualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EE5E1924-9B07-4D31-896D-0D8D34B5D9C9
[ThaliCore] Session.startOutputStream(with:) peer:EE5E1924-9B07-4D31-896D-0D8D34B5D9C9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,9 [6, 11, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.deinit peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0)
,2017-07-24 11:06:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","generation":0}]'
,2017-07-24 11:06:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","generation":0}'
,2017-07-24 11:06:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:06:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,1E5565-7CD1-4438-B15D-EB97D09CF081:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,51E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:06:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2jPrtKdGFG7gS4pUWq2M9Nh31f69hkrC","error":"Peer is unavailable","portNumber":null}'
2017-07-24 11:06:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2jPrtKdGFG7gS4pUWq2M9Nh31f69hkrC', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:06:36 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:06:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:06:36 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:06:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:951E5565-7CD1-4438-B15D-EB97D09CF081
2017-07-24 11:06:36 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-24 11:06:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2E623E57-D644-437A-B062-C493DD079F60 (syncValue: pV54U18FVn2Gc19jMoLM1gNpbcv8nrWk)'
2017-07-24 11:06:36 - DEBUG thaliMobileNativeTestUt,i,ls: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:s,essionNotConnected:) Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserRelay.init(session:generation:creat,eVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2E623E57-D644-437A-B062-C493DD079F60:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2E623E57-D644-437A-B062-C493DD079F60:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2E623E57-D644-437A-B062-C493DD079F60:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59892
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pV54U18FVn2Gc19jMoLM1gNpbcv8nrWk",,"error":null,"portNumber":59892}'
2017-07-24 11:06:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pV54U18FVn2Gc19jMoLM1gNpbcv8nrWk', error: 'null', listeningPort: '59892''
,2017-07-24 11:06:39 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2E623E57-D644-437A-B062-C493DD079F60:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [6, 11, 19, 20]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:06:39 - DEBUG testUtils: 'Got response data'
2017-07-24 11:06:39 - DEBUG testUtils: 'Got end'
ok 289 response body should match testData
ok 290 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:10087D13-05EC-4EC5-A858-75B42091AB0B
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 11:06:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 11:06:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 291 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 ,"Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliC,ore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserManager.disconnect peer:2E623E57-D644-437A-B062-C493DD079F60
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59892
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [6, 11, 20]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] Session.disconnect() peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:20 [6, 1,1]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-0,7-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:EE5E1924-9B07-4D31-896D-0D8D34B5D9C9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:EE5E1924-9B07-4D31-896D-0D8D34B5D9C9
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:EE5E1924-9B07-4D31-896D-0D8D34B5D9C9
,# will fail bad PSK connection between peers
,ok 292 FIX ME, PLEASE!!!
,# teardown
,ok 293 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-24 11:06:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 294 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:06:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-24 11:06:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 295 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:06:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 296 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 297 specific error should be returned
,# teardown
,2017-07-24 11:06:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 11:06:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 11:06:41 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 11:06:41 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 298 error should be null
ok 299 error should be null
,# setup
,ok 300 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 301 specific error should be returned
,# teardown
,ok 302 error should be null
ok 303 error should be null
,# setup
,ok 304 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'listening 59894'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 305 error should be null
ok 306 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive,":false,"advertisingActive":false}'
ok 307 error should be null
ok 308 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 11:06:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 309 error should be null
ok 310 error should be null
,# setup
,ok 311 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'listening 59895'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E176ADFB-84D7-453C-B941-E3F6A5BC2654
,[ThaliCore] Browser.startListening
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 312 error should be null
,ok 313 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 314 error should be null
,ok 315 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:06:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 316 error should be null
,ok 317 error should be null
,# setup
,ok 318 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'listening 59896'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "73914388-9CF6-421E-941F-0309BF60B4D6", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:73914388-9CF6-421E-941F-0309BF60B4D6
2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 319 error should be null
ok 320 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "73914388-9CF6-421E-941F-0309BF60B4D6", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:73914388-9CF6-421E-941F-0309BF60B4D6
20,17-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 321 error should be null
ok 322 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:73914388-9CF6-421E-941F-0309BF60B4D6
[ThaliCore] Advertiser.stopAdvertising() peerID:73914388-9CF6-421E-941F-0309BF60B4D6
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 11:06:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 323 error should be null
,ok 324 error should be null
,# setup
,ok 325 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'listening 59899'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 326 error should be null
ok 327 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
ok 328 error should be null
,ok 329 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:43 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 11:06:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 330 error should be null
ok 331 error should be null
,# setup
,ok 332 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-24 11:06:43 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 333 This should not cause wifi to fail
ok 334 native router should be bad
,# teardown
,ok 335 error should be null
ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-24 11:06:44 - DEBUG thaliMobileNativeWrapper: 'listening 59900'
ok 338 first call should succeed
ok 339 first call should succeed
ok 340 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 11:06:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-24 11:06:44 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 344 error should be null
ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-24 11:06:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 347 error should be null
ok 348 error should be null
,# setup
,ok 349 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8f966812-27c4-471c-bb8f-cb73f8959b4b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 350 should be calle,d once
ok 351 should not have been called more than once
,# teardown
,2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8f966812-27c4-471c-bb8f-cb73f8959b4b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 352 error should be null
ok 353 error should be null
,# setup
,ok 354 ThaliMobile should be stopped
,# can get the network status
,ok 355 network status should have certain non-empty properties
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 359 we have not added peer to the cache yet
,2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"68ed2575-645e-4769-83e8-f829ee08cf69","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 360 peer should be ,available
ok 361 cache contains native peer
2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"68ed2575-645e-4769-83e8-f829ee08cf69","connectionType":"MPCF","peerAvailable":false,"generation":0,",newAddressPort":null}'
ok 362 peer should be unavailable
ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 367 we have not added peer to the cache yet
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e407fd59-01da-4dd4-bfc6-c74dad5a35c2","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 368 peer should be available
ok 369 cache contains wifi peer
2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e407fd59-01da-4dd4-bfc6-c74dad5a35c2","connectionType":"tcp","peerAvailable":false,"generation":0,"newA,ddressPort":null}'
ok 370 peer should be unavailable
ok 371 peer has been removed from cache
,# teardown
,ok 372 error should be null
ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"11ca0eda-314b-422a-b8bd-ce0809f6bc1d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 375 first peer is available
2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b5ad782a-a460-49a6-bb6b-d2661cc10f78","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":,false}'
ok 376 second peer is available
ok 377 first and second peers are different
,# teardown
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"11ca0eda-314b-422a-b8bd-ce0809f6bc1d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b5ad782a-a460-49a6-bb6b-d2661cc10f78","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 378 error should be null
ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 381 should not be in cache at start
2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e764a592-ae78-45b2-a5f2-945ccfbdb3dd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 382 peer is available
,# teardown
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e764a592-ae78-45b2-a5f2-945ccfbdb3dd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-24 11:06:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 386 error should be null
ok 387 error should be null
,# setup
,ok 388 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-24 11:06:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1432b5e3-f1c9-4719-9047-88badb29d204","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 392 peer should be available
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1432b5e3-f1c9-4719-9047-88badb29d204","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 393 peer should be available
ok 394 should store correct generation
,# teardown
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1432b5e3-f1c9-4719-9047-88badb29d204","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 395 error should be null
ok 396 error should be null
,# setup
,ok 397 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-24 11:06:47 - DEBUG thaliMobileNativeWrapper: 'listening 59901'
2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"759f68e9-19a1-44a4-8aed-865cb17c7122","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 398 discovered correct peer
ok 399 got correct generation
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"759f68e9-19a1-44a4-8aed-865cb17c7122","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 400 discovered correct peer
ok 401 got correct generation
,# teardown
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"759f68e9-19a1-44a4-8aed-865cb17c7122","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:48 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-24 11:06:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:06:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 402 error should be null
ok 403 error should be null
,# setup
,ok 404 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-24 11:06:48 - DEBUG thaliMobileNativeWrapper: 'listening 59902'
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"62ee4277-18d6-48d5-a8d7-22b696c06473","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 405 discovered avai,lable peer
ok 406 peer is available
,# teardown
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"62ee4277-18d6-48d5-a8d7-22b696c06473","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:48 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:06:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 407 error should be null
,ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b2a112a1-7d46-4125-b537-a3bb45f5f20c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 410 peer should be available
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b2a112a1-7d46-4125-b537-a3bb45f5f20c","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 411 peer should be unavailable
,ok 412 should be removed from cache
,# teardown
,ok 413 error should be null
,ok 414 error should be null
,# setup
,ok 415 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'listening 59903'
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c00b3b67-1e62-4330-9485-75261dc905aa","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 416 first peer is expected to be available
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0a6f7050-b273-4abc-8d46-12cd3996757f","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 417 second peer is expected to be available
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0a6f7050-b273-,4abc-8d46-12cd3996757f","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 418 peer became unavailable
,ok 419 it was wifi peer
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0a6f7050-b273-4abc-8d46-12cd3996757f","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}',
ok 420 we found peer again
ok 421 it was wifi peer
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0a6f7050-b273-4abc-8d46-12cd3996757f","connectionType":"tcp","peerAvailable":false,,"generation":null,"newAddressPort":null}'
ok 422 peer became unavailable
ok 423 it was wifi peer
,# teardown
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c00b3b67-1e62-4330-9485-75261dc905aa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:06:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 424 error should be null
ok 425 error should be null
,# setup
,ok 426 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-24 11:06:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 427 error should be null
ok 428 error should be null
,# setup
,ok 429 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'listening 59904'
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4736ff18-3f0c-4f92-91b1-04e687d1dde7","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 430 first peer is expected to be available
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"45fdbac5-b88d-4914-84aa-9038a15d055d","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 431 second peer is expected to be available
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4736ff18-3f0c-4f92-91b1-04e687d1dde7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 432 pee,r became unavailable
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"45fdbac5-b88d-4914-84aa-9038a15d055d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 433 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:49 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 434 error should be null
,ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-24 11:06:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 437 error should be null
ok 438 error should be null
,# setup
,ok 439 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-24 11:06:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 440 error should be null
ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9fdaf6bf-e0c8-483e-a666-208557361928","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 443 peer discovered ,first time does not have new address
2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9fdaf6bf-e0c8-483e-a666-208557361928","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 444 address has not been changed
2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9fdaf6bf-e0c8-483e-a666-208557361928","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 445 new port handled correctly
2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9fdaf6bf-e0c8-483e-a666-208557361928","connectionType":"tcp","peerAvailable":tru,e,,"generation":20,"newAddressPort":true}'
ok 446 new host handled correctly
2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9fdaf6bf-e0c8-483e-a666-208557361928","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 447 newAddressPort is null for unavailable peers
,# teardown
,ok 448 error should be null
ok 449 error should be null
,# setup
,ok 450 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-24 11:06:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 451 error should be null
ok 452 error should be null
,# setup
,ok 453 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 454 NOT IMPLEMENTED # SKIP
,# teardown
,ok 455 error should be null
ok 456 error should be null
,# setup
,ok 457 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-24 11:06:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 458 error should be null
ok 459 error should be null
,# setup
,ok 460 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 461 should be equal
,# teardown
,ok 462 error should be null
ok 463 error should be null
,# setup
,ok 464 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-24 11:06:51 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 465 error should be null
ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-24 11:06:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 468 contains expected properties
ok 469 the same ho,stAddress
ok 470 the same portNumber
,# teardown
,2017-07-24 11:06:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 474 contains expected properties
ok 475 the same hostAddress
ok 476 the same portNumber
,# teardown
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 477 error should be null
ok 478 error should be null
,# setup
,ok 479 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'listening 59905'
2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0adc99ec-c0f1-4416-9f48-15369c21f867","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 480 Got specific error message
,# teardown
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0adc99ec-c0f1-4416-9f48-15369c21f867","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:52 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:06:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 481 error should be null
ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'listening 59906'
2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b7af75d6-b7a0-429e-bc89-5e8867b0a42b","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.disconnect peer:b7af75d6-b7a0-429e-bc89-5e8867b0a42b
,ok 484 native wrapper `disconnect` called once
ok 485 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b7af75d6-b7a0-429e-bc89-5e8867b0a42b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:52 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:06:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-24 11:06:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-24 11:06:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-24 11:06:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 495 error should be null
,ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-24 11:06:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-24 11:06:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-24 11:06:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 504 error should be null
ok 505 error should be null
,# setup
,ok 506 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-24 11:06:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 507 error should be null
ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'listening 59907'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8F73F8D0-AE66-48D4-B397-B574C5C8692C
[ThaliCore] Browser.startListening
2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3f824046-e697-44b5-b218-15e5f3c908de","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 510 Peer availabilities has one entry for our connection type
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7654b0be-d27a-4854-b8b6-0c50ff17cabd","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 511 Peer availabilities has one entry for our connection type
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3f824046-e697-44b5-b218-15e5f3c908de","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7654b0be-d27a-4854-b8b6-0c50ff17cabd","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:06:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-24 11:06:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:06:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 512 No peers
,ok 513 No peers
,ok 514 No peers
,# teardown
,ok 515 error should be null
,ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-24 11:06:55 - DEBUG thaliMobileNativeWrapper: 'listening 59908'
2017-07-24 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c451c667-2793-45f0-ac18-6bf9fb88d39f","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 518 1
ok 519 2
,2017-07-24 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e58a15e5-8ec2-45d0-931d-e968f896e082","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-24 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c451c667-2793-45f0-ac18-6bf9fb88d39f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e58a15e5-8ec2-45d0-931d-e968f896e082","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
,2017-07-24 11:06:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:55 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:06:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 520 error should be null
ok 521 error should be null
,# setup
,ok 522 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-24 11:06:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 523 error should be null
ok 524 error should be null
,# setup
,ok 525 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'listening 59909'
ok 526 error should be null
ok 527 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9EED0799-F500-45EE-9882-03,BB7687C630", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9EED0799-F500-45EE-9882-03BB7687C630
2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 528 error should be null
ok 529 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
[ThaliCore] Browser.startLi,stening
2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 530 error should be null
,ok 531 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}]'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2E623E57-D644-437A-B062-C493DD079F60 (syncValue: 0)'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2E,623E57-D644-437A-B062-C493DD079F60", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
2017-07-24 11:06:57 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","generation":0}]'
2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","generation":0}'
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:06:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
2017-07-24 11:06:57 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}]'
2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}'
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:06:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9EED0799-F500-45EE-9882-03BB7687C630:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
2017-07-24 11:06:58 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}]'
2017-07-24 11:06:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}'
,2017-07-24 11:06:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:06:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2E623E57-D644-437A-B062-C493DD079F60:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2E,623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,E623E57-D644-437A-B062-C493DD079F60", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 11:06:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 11:06:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:59 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CAD31C85-20E6-4BD1-A48E-7A308E222915 (syncValue: 1)'
,2017-07-24 11:06:59 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:06:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59915
,2017-07-24 11:07:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":59915}'
,2017-07-24 11:07:01 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8 (syncValue: 2)'
,2017-07-24 11:07:01 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [6, 11, 21]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0 state: notConnected -> connecting
,2017-07-24 11:07:03 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:07:03 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] Advertiser: session connected Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
[ThaliCore] Advertiser: session connected Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59919
,2017-07-24 11:07:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":59919}'
,[ThaliCore] BrowserManager.disconnect peer:2E623E57-D644-437A-B062-C493DD079F60
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [6, 11, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:07:06 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:07:06 - DEBUG testUtils: 'Got end'
,ok 532 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
,[ThaliCore] Session.session(_:peer:didChange:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] Session.startOutputStream(with:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,3 [6, 11, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
[ThaliCore] Session.startOutputStream(with:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,4 [6, 11, 21, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 11:07:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 11:07:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9EED0799-F500-45EE-9882-03BB7687C630
,2017-07-24 11:07:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:07:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 11:07:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 11:07:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:07:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:07:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsync,SocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:23
[ThaliCore] TCPClient.socketDidDisconnect(_:with,Error:) client disconnected
,[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:24
[ThaliCore] VirtualSocket.closeStreams() vs,ID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [6, 11, 21, 22, 24]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [6, 11, 21, 22]
,ok 533 error should be null
,ok 534 error should be null
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [6, 11, 21]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [6, 11]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remove,d, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 535 ThaliMobile should be stopped
,# test for data corruption
,2017-07-24 11:07:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 536 error should be null
ok 537 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 538 getPeerIdentifier
ok 539 getConnectionType
,ok 540 getActionType
,ok 541 getActionState
,ok 542 getPskIdentity
,ok 543 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 544 initial state
ok 545 after start
2017-07-24 11:07:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 546 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 547 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-24 11:07:11 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 548 clean kill
ok 549 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 550 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 551 forever agent should have it's own destroy method
ok 552 agent's destroy should be called
ok 553 agent's destroy should not be called again
ok 554 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 555 Entry counter must be 1
,ok 556 Entry exists
,ok 557 Size must be 1
,ok 558 Entry counter must be 2
,ok 559 Entry exists
,ok 560 Size must be 2
,ok 561 Entry counter must be 1
,ok 562 Entry exists
,ok 563 Size must be 3
,ok 564 Entry counter must be 2
,ok 565 Entry exists
,ok 566 Size must be 4
,ok 567 Entry 1_1 should not be found
,ok 568 Entry 1_1 does not exist
,ok 569 Size must be 3
,ok 570 Entry 1_2 should not be found
,ok 571 Entry 1_2 does not exist
,ok 572 Size must be 2
,ok 573 should be equal
,ok 574 Entry 2_1 should not be found
,ok 575 Entry 2_2 should not be found
,ok 576 Entry 2_1 does not exist
,ok 577 Entry 2_2 does not exist
,ok 578 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 579 Size must be100
,ok 580 Entries between 20 and MAXSIZE + 20 should exist
,ok 581 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 582 Entries between 6 and MAXSIZE + 4 should exist
,ok 583 Size should be MAXSIZE
ok 584 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 585 WAITING state entry should not be removed
,ok 586 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 587 Size should be MAXSIZE
,ok 588 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 589 Kill should be called once
,ok 590 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 591 is an agent
ok 592 enqueue is fine
ok 593 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 594 is an agent
ok 595 first enqueue is fine
ok 596 is an agent
ok 597 second enqueue is fine
ok 598 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 599 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 600 is an agent
,ok 601 good enqueue
,ok 602 Identity should match
,2017-07-24 11:07:16 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:07:16 - DEBUG testUtils: 'Got end'
,ok 603 Got expected response
,ok 604 Got psk call back
,# teardown
,2017-07-24 11:07:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 605 is an agent
ok 606 enqueue worked
ok 607 is an agent
ok 608 enqueue 2 worked
ok 609 enqueue is not available when stopped
,ok 610 start action is killed
,ok 611 killed action is still killed
ok 612 enqueued action when stopped is killed
,ok 613 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 614 good start
ok 615 good enqueue
,ok 616 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 617 null arg
ok 618 wrong arg type
ok 619 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 620 good enqueue
,ok 621 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 622 good enqueue
,ok 623 2nd good enqueue
ok 624 we are in the pool
ok 625 We are out of the pool
ok 626 Action was killed
ok 627 The original kill was called too
ok 628 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 629 good enqueue
ok 630 first kill
,ok 631 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 632 1st good enqueue
ok 633 2nd good enqueue
,ok 634 1st action is in the pool
ok 635 2nd action is in the pool
ok 636 1st action is out of the pool
ok 637 2st action is out of the pool
ok 638 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-24 11:07:19 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 639 Got right error
,ok 640 Start should not be called
,ok 641 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-24 11:07:19 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-24 11:07:19 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 642 Got right error
ok 643 Start should not be called
ok 644 Kill should have been calle,d at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-24 11:07:19 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 645 Got null
2017-07-24 11:07:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 646 is an agent
2017-07-24 11:07:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 647 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 648 Got Null
,ok 649 Got another null
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 650 is an agent
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 651 is an agent
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 652 Action 1 killed at least once
,ok 653 Action 1 went first
,ok 654 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 655 should have gotten null
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 656 Should have stopped nicely
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 657 Still looking for null
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 658 Yup, another null
,ok 659 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 660 Null 1
ok 661 (unnamed assert)
2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBlu,etooth, Peer Identifier: notificationAction'
ok 662 is an agent
ok 663 Null 3
ok 664 Replication not yet called
ok 665 Notification 2 not yet called
2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action, ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidB,luetooth, Peer Identifier: replicationAction'
ok 666 is an agent
,ok 667 Notification went first
ok 668 Notification 2 not called yet
2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Id,entifier: replicationAction'
2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection T,ype: AndroidBluetooth, Peer Identifier: notificationAction'
ok 669 is an agent
ok 670 Notification finished
ok 671 Replication finished
2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Acti,on Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 672 is an agent
,ok 673 First does not throw
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 674 is an agent
,ok 675 Second does not throw
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 676 is an agent
,ok 677 first ok
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 678 is an agent
,ok 679 second ok
,ok 680 third ok
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'action returned, successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
# teardown
,# setup
,# Client to server request coordinated
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'listening 59925'
,ok 681 error should be null
,ok 682 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:12B63DC0-3AAD-4086-9C02-4C78DF1E4303
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
,[ThaliCore] Browser.startListening
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:07:22 - INFO testThaliNotification: 'startListeningForAdvertisements'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] Session.startOutputStream(with:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [6, 11, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:25
,[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [6, 11]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] Session.startOutputStream(with:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,6 [6, 11, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] AdvertiserRelay.didC,loseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [6, 11]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] Session.startOutputStream(with:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,7 [6, 11, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [6, 11]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}]'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:07:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8 (syncValue: 3)'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0) found active relay
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":59919}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0)
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F51A3C8-A689-4B82-BAD8-DD34390017FE","generation":0}]'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F51A3C8-A689-4B82-BAD8-DD34390017FE","generation":0}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [6, 11, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4F51A3C8-A689-4B82-BAD8-DD34390017FE","peerAvailable":true,"generation":0,"portN,umber":null}'
,2017-07-24 11:07:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4F51A3C8-A689-4B82-BAD8-DD34390017FE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4F51A3C8-A689-4B82-BAD8-DD34390017FE (syncValue: 4)'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [6, 11]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 11:07:23 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:764C631C-B170-4A40-9D06-97350890569E
[ThaliCore] Advertiser: session connected Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:764C631C-B170-4A40-9D06-97350890569E state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0)
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EC9AF43F-E75B-4A72-9E65-674DD3ABC08B","generation":0}]'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"EC9AF43F-E75B-4A72-9E65-674DD3ABC08B","generation":0}'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"EC9AF43F-E75B-4A72-9E65-674DD3ABC08B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:07:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"EC9AF43F-E75B-4A72-9E65-674DD3ABC08B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
,[ThaliCore] Session.deinit peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:764C631C-B170-4A40-9D06-97350890569E
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:764C631C-B170-4A40-9D06-97350890569E state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59932
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":59932}'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for EC9AF43F-E75B-4A72-9E65-674DD3ABC08B (syncValue: 5)'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [6, 11, 29]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:764C631C-B170-4A40-9D06-97350890569E
[ThaliCore] Session.startOutputStream(with:) peer:764C631C-B170-4A40-9D06-97350890569E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [6, 11, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 11:07:26 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 59932,4F51A3C8-A689-4B82-BAD8-DD34390017FE'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:764C631C-B170-4A40-9D06-97350890569E
[ThaliCore] Session.startOutputStream(with:) peer:764C631C-B170-4A40-9D06-97350890569E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,1 [6, 11, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [6, 11, 29, 31]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [6, 11, 29, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:32 [6, 11, 29, 31]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [6, 11, 29]
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:59919
[ThaliCore] Session.disconnect() peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
,2017-07-24 11:07:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":"Session disconnected","portNumber":null}'
,2017-07-24 11:07:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 11:07:27 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-24 11:07:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.deinit peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
2017-07-24 11:07:27 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}]'
2017-07-24 11:07:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}'
,2017-07-24 11:07:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:07:27 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 11:07:27 - WARN thaliNotificationClient: 'peer is not avai,lable'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59939
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":59939,}'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8 (syncValue: 6)'
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", ge,neration: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":"Peer is unavailable","portNumber":null}'
2017-07-2,4 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F19FF2,86-5FF4-414C-B92A-B7A0BDE3CBB8 (syncValue: 7)'
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB,8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":"Peer is unavailable","portNumber":null}'
[ThaliCor,e] Session.init(session:identifier:connected:notConnected:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
[ThaliCore] Advertiser: session connected Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
,[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E state: notConnected -> connecting
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availab,ility changed event with {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentif,ier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:07:29 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
2017-07-24 11:07:29 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is u,navailable'
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:07:29 - DEBUG thaliMobileNativ,eWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
[ThaliCore] BrowserManager.disconnect peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8
,[ThaliCore] BrowserManager.disconnect peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [6, 11, 29, 33]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:07:30 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 59939,EC9AF43F-E75B-4A72-9E65-674DD3ABC08B'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [6, 11, 29]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [6, 11, 29, 34]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [6, 11, 29]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
,[ThaliCore] Session.session(_:peer:didChange:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
[ThaliCore] Session.startOutputStream(with:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,5 [6, 11, 29, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
[ThaliCore] Session.startOutputStream(with:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,6 [6, 11, 29, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
,[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:35 [6, 11, 29, 36]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [6, 11, 29]
,ok 683 Peer made successful https requests to all peers
ok 684 Peer received right amount of https requests
ok 685 HTTPS server received zero PSK Identities. Count:0
# teardown
,2017-07-24 11:07:37 - INFO testThaliNotification: 'Participants:3 Peers Replied to us:2 Peers requested to:2'
2017-07-24 11:07:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4F51A3C8-A689-4B82-BAD8-DD,34390017FE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 11:07:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"EC9AF43F-E75B-4A72-9E65-674DD3ABC08B,","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:12B63DC0-3AAD-4086-9C02-4C78DF1E4303
2017-07-24 11:07:37 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:07:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({",s,tarted":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 11:07:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdve,rtisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:07:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:07:37 - INFO thaliMobile: 'Filtered out dis,coveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:07:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:07:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:07:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 686 peerIdentifier should match
,ok 687 generation should match
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 good beacon
,ok 690 good preAmble
,ok 691 public keys match!
,ok 692 must return null after successful call
,ok 693 Once start returns the action should be in KILLED state
,# teardown
,2017-07-24 11:07:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 694 Response should be HTTP_BAD_RESPONSE
,ok 695 must return null after successful call
,# teardown
,2017-07-24 11:07:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 696 Response should be NETWORK_PROBLEM
,ok 697 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-24 11:07:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 698 Resolution should be BAD_PEER
,ok 699 correct error message
,# teardown
,2017-07-24 11:07:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 700 Call start once
,ok 701 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 702 must return null after successful call.
,# teardown
,2017-07-24 11:07:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 703 Should be Killed
,ok 704 Start after killed
,# teardown
,2017-07-24 11:07:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 705 Should be KILLED
ok 706 must return null after successful kill
,# teardown
,2017-07-24 11:07:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 707 Should be KILLED
ok 708 must return null after successful kill
,# teardown
,2017-07-24 11:07:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 709 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 710 must return null after successful call
,# teardown
,2017-07-24 11:07:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-24 11:07:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 711 Should be NETWORK_PROBLEM caused closing server socket
ok 712 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 713 Should be NETWORK_PROBLEM caused closing client socket
,ok 714 Should be Could not establish TCP connection
,# teardown
,2017-07-24 11:07:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 715 publicKeysToNotify cannot be null
ok 716 ecdh for local device cannot be null
ok 717 milliseconds cannot be less than 0
ok 718 milliseconds cannot be 0
ok 719 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 720 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 721 should be equal
,ok 722 should be equal
,ok 723 (unnamed assert)
,ok 724 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 725 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 726 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 727 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 728 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 729 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 730 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 731 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 732 should be equal
,ok 733 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 734 should be equal
,ok 735 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 736 right number of calls to address book
ok 737 good preAmble
,ok 738 good unencryptedKeyId
,ok 739 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 740 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 741 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 742 Matching numbers
,ok 743 We have an entry!
ok 744 keys match
,ok 745 secrets match
,ok 746 We have an entry!
,ok 747 keys match
,ok 748 secrets match
,ok 749 We have an entry!
,ok 750 keys match
,ok 751 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 752 Streams have same length
,ok 753 matching size
,ok 754 keys match
,ok 755 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 756 should be equal
,ok 757 peerDictionalty contains 2 peers
,ok 758 bluetooth peer's notification has correct connection type
,ok 759 tcp peer's notification has correct connection type
,2017-07-24 11:07:57 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-24 11:07:57 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 11:07:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 760 notification peer dictionary contains exactly 1 peer
2017-07-24 11:07:58 - WARN thaliNotificationClient: 'peer is not available'
ok 761 notification peer dictionary does not contain any peers
,2017-07-24 11:07:58 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 11:07:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 762 entry exists
,ok 763 entry is resolved
,# teardown
,2017-07-24 11:07:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 764 Action should be KILLED
ok 765 Peer state should be RESOLVED
,# teardown
,2017-07-24 11:07:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 766 hostAddress must match
,ok 767 portNumber must match
,ok 768 suggestedTCPTimeout must match
,ok 769 connectionType must match
,ok 770 peerIDs must match
,# teardown
,2017-07-24 11:08:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 771 Correct error
,# teardown
,2017-07-24 11:08:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 772 hostAddress must match
,ok 773 portNumber must match
,ok 774 suggestedTCPTimeout must match
,ok 775 connectionType must match
,ok 776 peerIds must match
,# teardown
,2017-07-24 11:08:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-24 11:08:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 777 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 11:08:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 778 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 11:08:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 779 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 11:08:03 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 780 action should be resolved with NETWORK_PROBLEM error
ok 781 correct number of requests
ok 782 correct number of failures
ok 783 correct final peer state
,# teardown
,2017-07-24 11:08:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-24 11:08:06 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-24 11:08:06 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 784 peerDictionary should become empty
,# teardown
,2017-07-24 11:08:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-24 11:08:06 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 785 failed with expected error
ok 786 peer state should be RESOLVED
,# teardown
,2017-07-24 11:08:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-24 11:08:07 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 787 First action failed
,ok 788 second action killed
# teardown
,2017-07-24 11:08:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 789 secrets are equal
,ok 790 Public key matches with the server key
ok 791 hostAddress must match
,ok 792 portNumber must match
,ok 793 suggestedTCPTimeout must match
ok 794 connectionType must match
,# teardown
,2017-07-24 11:08:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 795 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 796 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 797 All entries should be expired after 1 second
# teardown
,2017-07-24 11:08:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 798 All keys need to be available in the cache
,ok 799 All entries should be expired after 1 second
# teardown
,2017-07-24 11:08:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 800 Size of the cache should be 2
ok 801 Cache doesn't contain dictionary1
,ok 802 Size of the cache should be 1
ok 803 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-24 11:08:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 804 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 805 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-24 11:08:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 806 StartUpdateAdvertisingAndListening should not be called
,ok 807 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 808 no error
,ok 809 should be 204
,# teardown
,2017-07-24 11:08:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 810 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 11:08:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 811 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 11:08:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 812 no error
,ok 813 should be 200
,ok 814 should be equal
,ok 815 should be equal
,ok 816 (unnamed assert)
,ok 817 no error
,ok 818 should be 204
,# teardown
,2017-07-24 11:08:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 819 error should be null
,ok 820 should be 204
,# teardown
,2017-07-24 11:08:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 821 should be 404
# teardown
,2017-07-24 11:08:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 822 equal keys
,ok 823 not equal connection type
,ok 824 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-24 11:08:19 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 825 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 826 second cleared dictionary
,2017-07-24 11:08:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 827 First start and on called correctly
,ok 828 First stop and removeListener called correctly
,ok 829 first action kill called
,ok 830 second action kill called
,ok 831 first cleared dictionary
,ok 832 first cleared pool
,ok 833 second cleared dictionary
,ok 834 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 835 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-24 11:08:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 836 listener has been set
,ok 837 peer dictionary has expected number of entries
,ok 838 Dictionary and pool have same action
,ok 839 ads match
,ok 840 PouchDB matches
,ok 841 DB Names match
,ok 842 public keys match
,ok 843 peer dictionary has expected number of entries
,ok 844 Dictionary and pool have same action
,ok 845 ads match
,ok 846 PouchDB matches
,ok 847 DB Names match
,ok 848 public keys match
,2017-07-24 11:08:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 849 start called once
,ok 850 One entry left
,ok 851 Dictionary and pool have same action
,ok 852 Start never called
,ok 853 Kill called once
,ok 854 no entries left
,ok 855 Third action is dead
,ok 856 peer dictionary has expected number of entries
,ok 857 Dictionary and pool have same action
,ok 858 ads match
,ok 859 PouchDB matches
,ok 860 DB Names match
,ok 861 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-24 11:08:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 11:08:21 - DEBUG thaliMobileNativeWrapper: 'listening 59995'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] Browser.startListening
,2017-07-24 11:08:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3
,2017-07-24 11:08:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] Advertiser: session connected Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D8CC952-620F-4C53-BCCF-6430782E2A13", generation: 0)
2017-07-24 11:08:23 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2D8CC952-620F-4C53-BCCF-6430782E2A13","generation":0}]'
2017-07-24 11:08:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2D8CC952-620F-4C53-BCCF-6430782E2A13","generation":0}'
,2017-07-24 11:08:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2D8CC952-620F-4C53-BCCF-6430782E2A13","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:08:23 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2D8CC952-620F-4C53-BCCF-6430782E2A13","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 11:08:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 2D8CC952-620F-4C53-BCCF-6430782E2A13 (syncValue: 8)'
2017-07-24 11:08:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D8CC952-620F-4C53,-BCCF-6430782E2A13", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2D8CC952-620F-4C53-BCCF-6430782E2A13", generation: 0)
[ThaliCore] Session.init(session:identifier:connected,:,notConnected:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Advert,iser: session connected Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0)
,2017-07-24 11:08:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"63570569-B1AE-4581-979F-3BFBFB102A51","generation":0}]'
2017-07-24 11:08:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"63570569-B1AE-4581-979F-3BFBFB102A51","generation":0}'
,2017-07-24 11:08:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"63570569-B1AE-4581-979F-3BFBFB102A51","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:08:24 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"63570569-B1AE-4581-979F-3BFBFB102A51","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,7 [6, 11, 29, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,37
[ThaliCore] VirtualSocket.deinit vsID:37 [6, 11, 29]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [6, 11, 29, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [6, 11, 29, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2D8CC952-620F-4C53-BCCF-6430782E2A13", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60001
,2017-07-24 11:08:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":60001}'
,2017-07-24 11:08:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 63570569-B1AE-4581-979F-3BFBFB102A51 (syncValue: 9)'
,2017-07-24 11:08:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [6, 11, 29, 38, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [6, 11, 29, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
,[ThaliCore] Session.session(_:peer:didChange:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [6, 11, 29, 38, 39, 40, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [6, 11, 29, 38, 39, 41, 42]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [6, 11, 29, 38, 39, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [6, 11, 29, 38, 39, 41, 42, 43, 44]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [6, 11, 29, 38, 39, 41, 42, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,44
[ThaliCore] VirtualSocket.deinit vsID:44 [6, 11, 29, 38, 39, 41, 42, 43, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,6 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 11:08:27 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0 state: notConnected -> connecting
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 51, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 51, 52, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket ,closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] Virtua,lSocket.closeStreams() vsID:51
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 52, 53, 54]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,5 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 52, 53, 54, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 53, 54, 55]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[T,haliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 53, 54, 55, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-24 11:08:27 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:55 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 53, 54, 56]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] VirtualSocket.deinit vsID:56 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 53, 54]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) ,client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 53, 54, 57]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 54, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,8 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 54, 57, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] VirtualSocket.deinit vsID:57 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 54, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60023
2017-07-24 11:08:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":60023,}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [6, 11, 29, 38, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 54, 58, 59]
[ThaliCore] Bro,wserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputSt,ream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Thali,Core] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [6, 11, 29, 39, 41, 42, 43, 45, 46, 47, 48, 49, 50, 54, 58, 59]
[ThaliCore] VirtualSocket.hand,leEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] AdvertiserRelay.didClos,e,VirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunL,oop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [6, 11, 29, 41, 42, 43, 45, 46, 47, 48, 49, 50, 54, 58, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wit,hError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [6, 11, 29, 41, 42, 43, 46, 47, 48, 49, 50, 54, 58, 59]
[T,haliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore,] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:41 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 54, 58, 59]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 54, 58]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 54, 58, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:08:29 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 54, 58, 60, 61]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:61
[ThaliCore] VirtualSocket.deinit vsID:61 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 54, 58, 60]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 54, 58, 60, 62]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:08:30 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 54, 58, 60, 62, 63]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] VirtualSocket.deinit vsID:54 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 58, 60, 62, 63]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 58, 60, 62, 63, 64]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:62
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 58, 60, 63, 64]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 58, 60, 63, 64, 65]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,64
[ThaliCore] VirtualSocket.deinit vsID:64 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 58, 60, 63, 65]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) clie,nt disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [6, 11, 29, 42, 43, 46, 47, 48, 49, 50, 58, 60, 63, 65, 66]
[ThaliCore] BrowserRela,y.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:08:30 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [6, 11, 29, 42, 43, 47, 48, 49, 50, 58, 60, 63, 65, 66]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,48
[ThaliCore] VirtualSocket.deinit vsID:48 [6, 11, 29, 42, 43, 47, 49, 50, 58, 60, 63, 65, 66]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [6, 11, 29, 42, 43, 47, 50, 58, 60, 63, 65, 66]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disco,nnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [6, 11, 29, 42, 43, 47, 50, 60, 63, 65, 66]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnec,ted
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 11:08:30 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-24 11:08:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-24 11:08:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
2017-07-24 11:08:32 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:60
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:66
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [6, 11, 29, 42, 43, 47, 50, 63, 65, 66]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler sta,te:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [6, 11, 29, 42, 43, 47, 50, 65, 66]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited Ru,n,Loop vsID:66
[ThaliCore] VirtualSocket.deinit vsID:66 [6, 11, 29, 42, 43, 47, 50, 65]
,2017-07-24 11:08:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-24 11:08:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
2017-07-24 11:08:33 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by r,emote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnec,tHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserI,n,fo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescriptio,n=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket c,losed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] VirtualSocket.deinit vsI,D:43 [6, 11, 29, 42, 47, 50, 65]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCo,r,e] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.closeStreams() vsID:47
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.closeStreams() vsID:50
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:65
[ThaliCore] BrowserRelay.did,CloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [6, 11, 29, 42, 50, 65]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] ,VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [6, 11, 29, 42, 65]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:65
[ThaliCore] VirtualSocket.d,e,init vsID:65 [6, 11, 29, 42]
,2017-07-24 11:11:21 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-24 11:11:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:11:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:11:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:11:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4,AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4,AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4,AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4,AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4,AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4,AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-24 11:18:21 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-24 11:18:21 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-24 11:,18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-24 11:18:21 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: passed - another'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***T,EST_LOGGER result: passed - test sinon sansbox spy'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox ,stub override'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-24 ,11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request coordinated'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated pull replication from notification test, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1,-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/bluebird/,js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-07-24 11:18:21 ,- ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-24 11:18:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4,AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 862 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-24 11:18:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4,AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4,AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:21:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:21:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4,AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA,1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:21:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9DD16BA0-2E47-4AA1-A0D1-AA77B27E7C41/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
