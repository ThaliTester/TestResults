#### Test 1133518510faaea9_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1133518510faaea9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/A71E373C-568E-45E1-B2DD-2E2110A34DB1/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/A71E373C-568E-45E1-B2DD-2E2110A34DB1/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1133518510faaea9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1133518510faaea9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59513"
,(lldb)     command script import "/tmp/A71E373C-568E-45E1-B2DD-2E2110A34DB1/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
JXcore engine is started
,2017-07-14 11:27:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:27:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:27:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:27:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:27:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:27:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:27:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5BFBB530-4F1E-4188-973D-CF0B27FB58C7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5BFBB530-4F1E-4188-973D-CF0B27FB58C7
Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B1024812-A6BB-41BE-9564-74C0410670B9
,[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
,AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D6069C10-3642-4D28-9C37-AE27DA0163EF
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "378AC203-9E9F-4F0C-BEE8-C9A9F0C25699", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:378AC203-9E9F-4F0C-BEE8-C9A9F0C25699
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:378AC203-9E9F-4F0C-BEE8-C9A9F0C25699:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "378AC203-9E9F-4F0C-BEE8-C9A9F0C25699", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-14 11:27:12 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.823351979255676
,2017-07-14 11:27:12 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-07-14 11:27:12 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:378AC203-9E9F-4F0C-BEE8-C9A9F0C25699:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "378AC203-9E9F-4F0C-BEE8-C9A9F0C25699", generation: 0)
,2017-07-14 11:27:15 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-14 11:27:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-14 11:27:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-14 11:27:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-14 11:27:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-14 11:27:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-14 11:27:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-14 11:27:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-14 11:27:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-14 11:27:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-14 11:27:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-14 11:27:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-14 11:27:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-14 11:27:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-14 11:27:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-14 11:27:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-14 11:27:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-14 11:27:20 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-14 11:27:20 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-14 11:27:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:28:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:28:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:28:17 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-07-14 11:28:17 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-14 11:28:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-14 11:28:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-14 11:28:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-14 11:28:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-14 11:28:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-14 11:28:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-14 11:28:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-14 11:28:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-14 11:28:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-14 11:28:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-14 11:28:51 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-14 11:28:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-14 11:28:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FCA4CFB7-61FE-4630-A11C-C778F329BA27
[ThaliCore] Browser.startListening
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2CD31BB6-E3A1-43BA-855D-EB08E8D2B9D3
,[ThaliCore] Browser.startListening
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C7305F25-B640-4914-B9E0-10B0C41FD163", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C7305F25-B640-4914-B9E0-10B0C41FD163
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:28:58, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Adve,rtiser.stopAdvertising()
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUp,date (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6188FE25-BD95-4097-A80F-33F128ADA448", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6188FE25-BD95-4097-A80F-33F128ADA448
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6188FE25-BD95-4097-A80F-33F128ADA448", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:6188FE25-BD95-4097-A80F-33F128ADA448
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:28:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:,28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Sho,uld be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:80DF8A94-63B2-4251-838F-96CD4A4899AA
2017-07-14 1,1:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B2931A7E-C477-4D78-B8FA-995DBD1A81B1
[Thali,C,ore] Browser.startListening
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:28E6A239-B69C-4274-A411-DD9E8D1E94BB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "28E6A239-B69C-4274-A411-DD9E8D1E94BB", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFDB3600-5C66-4F43-8D70-1D53F58FC5A4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A4", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80DF8A94-63B2-4251-838F-96CD4A4899AA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:29:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:29:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 93 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:29:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:29:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD
2017-07-14 1,1:29:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AD3A8590-4641-4F73-9C1E-9811AE25043E
[ThaliCore] Browser.startListening
2017-07-14 11:29:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-14 11:29:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:28E6A239-B69C-4274-A411-DD9E8D1E94BB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "28E6A239-B69C-4274-A411-DD9E8D1E94BB", generation: 0)
2017-07-14 11:29:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"28E6A239-B69C-4274-A411-DD9E8D1E94BB","generation":0}'
2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 28E6A239-B69C-4274-A411-DD9E8D1E94BB, (syncValue: S8FjoA9pOWCdi7KoBiNjx44BBknHbWvO)'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFDB3600-5C66-4F43-8D70-1D53F58FC5A4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A,4", generation: 0)
2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "28E6A239-B69C-4274-A411-DD9E8D1E94BB", generation: 0) new relay
[Thal,i,Core] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "28E6A239-B69C-4274-A411-DD9E8D1E94BB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:28E6A239-B69C-4274-A411-DD9E8D1E94BB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CFDB3600-5C66-4F43-8D70-1D53F58FC5A4","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CFDB3600-5C66-4F43-8D70-1D53F58FC5A4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A4", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"7B90ADCE-E704-407C-9CE8-7BB8430AD315","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
2017-07-14 11:29:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F6B5DBB-1C61-4809-A491-89BBC874CDFD","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:28E6A239-B69C-4274-A411-DD9E8D1E94BB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "28E6A239-B69C-4274-A411-DD9E8D1E94BB", generation: 0)
[ThaliCore] Session.disconnect() peer:28E6A239-B69,C-4274-A411-DD9E8D1E94BB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:28E6A239-B69C-4274-A411-DD9E8D1E94BB:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "28E6A239-B69C-4274-A411-DD9E8D1E94BB", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:28E6A239-B69C-4274-A411-DD9E8D1E94BB:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "28E6A239-B69C-4274-A411-DD9E8D1E94BB", genera,tion: 0)
,2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"S8FjoA9pOWCdi7KoBiNjx44BBknHbWvO","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:08 - DEBUG thaliMobileNativeTestUtils: 'Got mul,tiConnectResolved -syncValue: 'S8FjoA9pOWCdi7KoBiNjx44BBknHbWvO', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"28,E6A239-B69C-4274-A411-DD9E8D1E94BB","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 11:29:08 -, DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"28E6A239-B69C-4274-A411-DD9E8D1E94BB","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Filt,ered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 11:29:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7B90ADCE-E704-407C-9CE8-7BB8430AD315 (syncValue: SKQqAE8QVJAKMfK8AsHyE38CeselyIdT)'
,2017-07-14 11:29:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49948
2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SKQqAE8QVJAKMfK8AsHyE38CeselyIdT","error":null,"portN,umber":49948}'
2017-07-14 11:29:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SKQqAE8QVJAKMfK8AsHyE38CeselyIdT', error: 'null', listeningPort: '49948''
,2017-07-14 11:29:12 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,2017-07-14 11:29:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 ,11:29:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
,ok 101 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConne,ctionsAndDisconnectClients() port:49948
,[ThaliCore] Session.disconnect() peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Pee,r(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
,# setup
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:630D69F0-7B0D-4353-B1D3-72041CE8B2A3
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FDA7BE12-20BF-4092-8157-C88DE6F4E901
[ThaliCore] Browser.startListening
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:29:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
2017-07-14 11:29:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7B90ADCE-E704-407C-9CE8-7BB8430AD315","generation":0}'
2017-07-14 11:29:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7B90ADCE-E704-407C-9CE8-7BB8430AD315, (syncValue: VVmpdyjPSQnu7hpBO0ZEpKzTfZ9aUYue)'
2017-07-14 11:29:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F6B5DBB-1C61-4809,-A491-89BBC874CDFD:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
[Tha,liCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:29:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F6B5DBB-1C61-4809-A491-89BBC874CDFD","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,2017-07-14 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3EF12D56-06E7-4BD7-B33A-43FCA5D374FE","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0)
,2017-07-14 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"14DF6D47-0838-4CD4-8191-E53A4CB3D543","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0 state: notConnected -> notConnected
,[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generati,on: 0)
,2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VVmpdyjPSQnu7hpBO0ZEpKzTfZ9aUYue","error":"Connection could not be established","portNumber":null}'
,2017-07-14 11:29:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VVmpdyjPSQnu7hpBO0ZEpKzTfZ9aUYue', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7B90ADCE-E704-407C-9CE8-7BB8430AD315","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7B90ADCE-E704-407C-9CE8-7BB8430AD315","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 11:29:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3EF12D56-06E7-4BD7-B33A-43FCA5D374FE (syncValue: lj7Z1sopnNSOraPALy2SnzE8ZLGiD4VV)'
,2017-07-14 11:29:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:38A4A1D1-D0AB-482D-85EE-4022A956DB3C
[ThaliCore] Advertiser: session connected Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:38A4A1D1-D0AB-482D-85EE-4022A956DB3C state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:38A4A1D1-D0AB-482D-85EE-4022A956DB3C
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49954
,2017-07-14 11:29:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lj7Z1sopnNSOraPALy2SnzE8ZLGiD4VV","error":null,"portNumber":49954}'
2017-07-14 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'l,j7Z1sopnNSOraPALy2SnzE8ZLGiD4VV', error: 'null', listeningPort: '49954''
,Connecting to the localhost:49954
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
,Connected to the localhost:49954
,2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:38A4A1D1-D0AB-482D-85EE-4022A956DB3C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:38A4A1D1-D0AB-482D-85EE-4022A956DB3C
,[ThaliCore] Session.startOutputStream(with:) peer:38A4A1D1-D0AB-482D-85EE-4022A956DB3C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 11:29:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,Active":false}'
,2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConne,ctionsAndDisconnectClients() port:49954
[ThaliCore] Session.disconnect() peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:38A4A1D1-D0AB-482D-85EE-4022A956DB3C state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:38A4A1D1-D0AB-482D-85EE-4022A956DB3C
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:38A4A1D1-D0AB-482D-85EE-4022A956DB3C
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FFF4B219-CD64-4984-A16E-09A0AC4255C5
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:29:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C
[ThaliCore] Browser.startListening
2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-14 11:29:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0)
2017-07-14 11:29:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"14DF6D47-0838-4CD4-8191-E53A4CB3D543","generation":0}'
2017-07-14 11:29:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 14DF6D47-0838-4CD4-8191-E53A4CB3D543, (syncValue: 6pzGRgnGpwlJ0hUSaxZJwj9F6BB0KKdb)'
2017-07-14 11:29:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) fou,nd peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,2017-07-14 11:29:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3EF12D56-06E7-4BD7-B33A-43FCA5D374FE","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0)
,2017-07-14 11:29:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F12BAB81-3393-4AA2-9828-2D573BD80FEA","generation":0}'
,2017-07-14 11:29:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"278B96CA-1D44-46A9-9D5A-17875731F8E8","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", genera,tion: 0)
2017-07-14 11:29:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6pzGRgnGpwlJ0hUSaxZJwj9F6BB0KKdb","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:34 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '6pzGRgnGpwlJ0hUSaxZJwj9F6BB0KKdb', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"14DF6D47-0838-4CD4-8191-E53A4CB3D543","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 11:29:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"14DF6D47-0838-4CD4-8191-E53A4CB3D543","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:34 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3EF12D56-06E7-4BD7-B33A-43FCA5D374FE (syncValue: H5YSPSS,nIT5EF2uy8std0uzNyg1s6U5M)'
2017-07-14 11:29:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374F,E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
[ThaliCore] Session.disconnect() peer:3EF12D56-06E,7-4BD7-B33A-43FCA5D374FE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,2017-07-14 11:29:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"H5YSPSSnIT5EF2uy8std0uzNyg1s6U5M","error":"Connection could not be established","portNumber":null}'
,2017-07-14 11:29:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'H5YSPSSnIT5EF2uy8std0uzNyg1s6U5M', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 11:29:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3EF12D56-06E7-4BD7-B33A-43FCA5D374FE","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:29:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 11:29:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier,":"3EF12D56-06E7-4BD7-B33A-43FCA5D374FE","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3
[ThaliCore] Session.session(_:peer:didChange,:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3 state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
2017-07-14 11:29:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:40 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F12BAB81-3393-4AA2-9828-2D573BD80FEA (syncValue: GvICXh2,0D7nuFceqSX1SZuhb5RmqyrUS)'
2017-07-14 11:29:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FE,A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3
[ThaliCore] Session.startOutputStream(with:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3
[ThaliCore] Session.startOutputStream(with:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3
,[ThaliCore] Session.startOutputStream(with:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 3, 4, 5]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (10240 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received all data: d2Ai07SwVz9qEokaBqwsjdYT0LfPsLl9aoP5guzkGywRRyTXCLzmuf2yBzTD2Na2oE2NdTkfvDwBX7QQk6Vt8e2D9A5t,PudjG10HNK5kg17Vj0ITwhYNwTSmNunhpNCSNdrpatbKodKbgf8yNSuULRiLLxGuUmDrMDbaZPt5qC1JfwB9QSzDdanSnDtoW3ms3MBpZAewdLed2jbsISWPktdKwK61EIUyyH2Y2bMy4baiqGqdTH2u4aaAJ6XBAbrsokZhorjCUevm6D9Uk3bvUdssy5iRaCjQmvnFPVb4l3ricvN2VTQiM2oUvmm0UE2c5lTi4RFRl0H8YIhBUrV3nDnB5Uzu,XNzh7qzxUgVhFqr5wXfgHmoO1Mqt1UWk1MOY0mHGazAkDRksOvyHRY3Xb2Qy4IewpzfygckyYBpWUuqu6soL0G6J8fTAuX58eqhxrLGg8rUBSbCYvDHmqYHfDH5MGw9ZSqGv2oqwIiBrEavrEgOGNMLVIwSmLHAITIcmu0MqYjgjba1gljUabnqYM1ryjXE5WOhKdqEhnazgjvfDqqMlFB2ivYhvUgEIGQPEmxD8oRgms01FyEIKmlxud6jzDKpt,tLVXVCvx9SdqTb3QjpgtrzqAuSMc8lVmdgbVLXBR0qt49PAJyQ9l5Ip623Vqn142e54HRjIm4qF4U24iMlmwlo3cNRU2FlceM5RWqV3hDiYIooeKWxeRJKQuC1T1b9EQ0cyFEhjKCNB0oCv4jtSsNWdZUnMH2foa0TOmd8KuCNnkHWOpDJQDCacTID0Snmqnjt7BMdz4jgBKGcoP7Iz6G67BtX05WKwLfIKthW7xiniwZZNHqDzfZErlPOGxa5gj,EqIQohpshCuhbZFwT5QUC31RB6iylDq8vY3GLSEPoFfDw8Fbr8CLGKAVgouHEEwbhhpGEOt0DlS8po38pLwhQJ,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:3,
[ThaliCore] VirtualSocket.deinit vsID:3 [2, 4, 5]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,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'
2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4,
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [2, 5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49969
,2017-07-14 11:29:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GvICXh20D7nuFceqSX1SZuhb5RmqyrUS","error":null,"portNumber":49969}'
,2017-07-14 11:29:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GvICXh20D7nuFceqSX1SZuhb5RmqyrUS', error: 'null', listeningPort: '49969''
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,Connecting to the localhost:49969
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,Connecting to the localhost:49969
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,Connecting to the localhost:49969
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 5, 6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49969
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 5, 6, 7, 8]
,Connected to the localhost:49969
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49969
,ok 109 correct string length
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-14 11:29:44 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-14 11:29:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 11:29:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 11:29:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [2, 5, 7, 8]
ok 112 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [2, 5, 8]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [2, 5]
,ok 113 got the same data back
,ok 114 got the same data back
,# teardown
,2017-07-14 11:29:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:29:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7765DE71-9DF4-416D-9138-EBDD851164D3
ok 115 Should be a,ble to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49969
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:7765DE71-9DF4-416D-9138-EBDD851164D3
,# setup
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:29:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5C412DB4-3630-41E3-B6E7-1228683AFE89
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:39134FA1-97AB-4820-914B-6C6D335,6CA8D
[ThaliCore] Browser.startListening
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-14 11:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
2017-07-14 11:29:45 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F12BAB81-3393-4AA2-9828-2D573BD80FEA","generation":0}'
2017-07-14 11:29:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F12BAB81-3393-4AA2-9828-2D573BD80FEA, (syncValue: aGesq4lXXwVDm7lGEq7hLDsbtBUuJg0o)'
2017-07-14 11:29:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"278B96CA-1D44-46A9-9D5A-17875731F8E8","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
,2017-07-14 11:29:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0E8F36F6-99AE-405C-9D86-AFF2583B9FB5","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8951314-1504-4B26-B452-4EE45DC1E5BE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8951314-1504-4B26-B452-4EE45DC1E5BE", generation: 0)
,2017-07-14 11:29:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C8951314-1504-4B26-B452-4EE45DC1E5BE","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", genera,tion: 0)
2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aGesq4lXXwVDm7lGEq7hLDsbtBUuJg0o","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:51 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'aGesq4lXXwVDm7lGEq7hLDsbtBUuJg0o', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F12BAB81-3393-4AA2-9828-2D573BD80FEA","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F12BAB81-3393-4AA2-9828-2D573BD80FEA","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 11:29:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 278B96CA-1D44-46A9-9D5A-17875731F8E8 (syncValue: IFwgQfxbwHBJSJq1XvOOe3QFwHoD5GgJ)'
,2017-07-14 11:29:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0)
[ThaliCore] Session.disconnect() peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", genera,tion: 0)
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IFwgQfxbwHBJSJq1XvOOe3QFwHoD5GgJ","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'IFwgQfxbwHBJSJq1XvOOe3QFwHoD5GgJ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"278B96CA-1D44-46A9-9D5A-17875731F8E8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,11:29:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"278B96CA-1D44-46A9-9D5A-17875731F8E8","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0E8F36F6-99AE-405C-9D86-AFF2583B9FB5 (syncValue: 8m9xKjS,X5gS0jzi38Sgx9BsrFIp136wo)'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A3F0BDA-1A8E-48C4-BB6C-57D36F8E777E
[ThaliCore] Advertiser: session connected Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9A3F0BDA-1A8E-48C4-BB6C-57D36F8E777E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49981
2017-07-14 11:29:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8m9xKjSX5gS0jzi38Sgx9BsrFIp136wo",,"error":null,"portNumber":49981}'
2017-07-14 11:29:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8m9xKjSX5gS0jzi38Sgx9BsrFIp136wo', error: 'null', listeningPort: '49981''
Connecting to the localhost:49981
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [2, 5, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49981
,2017-07-14 11:29:59 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-14 11:29:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [2, 5]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket err,or:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9A3F0BDA-1A8E-48C4-BB6C-57D36F8E777E
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A3F0BDA-1A8E-48C4-BB6C-57D36F8E777E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A3F0BDA-1A8E-48C4-BB6C-57D36F8E777E
[ThaliCore] Session.startOutputStream(with:) peer:9A3F0BDA-1A8E-48C4-BB6C-57D36F8E777E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [2, 5, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [2, 5]
,2017-07-14 11:30:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:30:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:0E8F36F6-99AE-405C-9D86-AFF258,3B9FB5
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.session(_:peer:didChange:) peer:9A3F0BDA-1A8E-48C4-BB6C-57D36F8E777E state: connected -> notConnected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49981
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
,[ThaliCore] Session.disconnect() peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:9A3F0BDA-1A8E-48C4-BB6C-57D36F8E777E
[ThaliCore] AdvertiserRelay.deinit
[Th,aliCore] Session.deinit peer:9A3F0BDA-1A8E-48C4-BB6C-57D36F8E777E
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
,# setup
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4C30EC80-858C-4E61-957C-3AAAD5A8369E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4C30EC80-858C-4E61-957C-3AAAD5A8369E
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:30:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:11B1710A-4AC0-48A7-A91D-941826AA5C81
[ThaliCore] Browser.startList,ening
2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:30:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tr,ue}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8951314-1504-4B26-B452-4EE45DC1E5BE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8951314-1504-4B26-B452-4EE45DC1E5BE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C8951314-1504-4B26-B452-4EE45DC1E5BE","generation":0}'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C8951314-1504-4B26-B452-4EE45DC1E5BE (syncValue: 8Zs0tfktxa8GBJ4xXwDz5NKd7Eduy84D)'
2017-07-14 11:30:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "C8951314-1504-4B26-B452-4EE45DC1E5BE", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C8951314-1504-4B26-B452-4EE45DC1E5BE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C8951314-1504-4B26-B452-4EE45DC1E5BE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0E8F36F6-99AE-405C-9D86-AFF2583B9FB5","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
2017-07-14 11:30:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3203DACF-B417-4CCC-94E9-26751E12B3CC","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0)
2017-07-14 11:30:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A4101E0A-2D4F-4307-AF8E-D44CB4B5801D","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C30EC80-858C-4E61-957C-3AAAD5A8369E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C30EC80-858C-4E61-957C-3AAAD5A8369E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8951314-1504-4B26-B452-4EE45DC1E5BE:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "C8951314-1504-4B26-B452-4EE45DC1E5BE", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:C8951314-1504-4B26-B452-4EE45DC1E5BE:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "C8951314-1504-4B26-B452-4EE45DC1E5BE", genera,tion: 0)
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8Zs0tfktxa8GBJ4xXwDz5NKd7Eduy84D","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '8Zs0tfktxa8GBJ4xXwDz5NKd7Eduy84D', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"C8951314-1504-4B26-B452-4EE45DC1E5BE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 11:30:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C8951314-1504-4B26-B452-4EE45DC1E5BE","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:30:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0E8F36F6-99AE-405C-9D86-AFF2583B9FB5 (syncValue: UVNhqc6,C33DPPHFreyR19DldqK0GBBLV)'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB,5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", genera,tion: 0)
2017-07-14 11:30:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UVNhqc6C33DPPHFreyR19DldqK0GBBLV","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:30:12 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'UVNhqc6C33DPPHFreyR19DldqK0GBBLV', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:30:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"0E8F36F6-99AE-405C-9D86-AFF2583B9FB5","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:30:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 11:30:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0E8F36F6-99AE-405C-9D86-AFF2583B9FB5","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:30:12 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3203DACF-B417-4CCC-94E9-26751E12B3CC (syncValue: EdWmn0z,zrM7wwJdXOVEJZdzw4v4qF4HQ)'
2017-07-14 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3203DACF-B417-4CCC-94E9-26751E12B3C,C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49993
2017-07-14 11:30:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EdWmn0zzrM7wwJdXOVEJZdzw4v4qF4HQ",,"error":null,"portNumber":49993}'
2017-07-14 11:30:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EdWmn0zzrM7wwJdXOVEJZdzw4v4qF4HQ', error: 'null', listeningPort: '49993''
,Connecting to the localhost:49993
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
,Connected to the localhost:49993
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [2, 5, 11]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 124 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:11
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,# teardown
,2017-07-14 11:30:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:30:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:3203DACF-B417-4CCC-94E9-26751E12B3CC
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConne,ctionsAndDisconnectClients() port:49993
[ThaliCore] Session.disconnect() peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
,# setup
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "20216A23-DEEF-4A74-AC88-F693C37C1439", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:20216A23-DEEF-4A74-AC88-F693C37C1439
,2017-07-14 11:30:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 Ready to advertise
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:59F81310-4987-49B1-A096-18190F148A1F
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 128 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8951314-1504-4B26-B452-4EE45DC1E5BE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8951314-1504-4B26-B452-4EE45DC1E5BE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C176BE14-FC26-4A57-A85E-77356D3F97EA:0
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(,uuid: "C176BE14-FC26-4A57-A85E-77356D3F97EA", generation: 0)
2017-07-14 11:30:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
ok 129 stop ads worked
[ThaliCor,e] BrowserManager.foundPeerHandler peer:Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
2017-07-14 11:30:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-14 11:30:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 133 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 134 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CA856195-532D-4FE8-8A7D-DC19028312D9
,[ThaliCore] Browser.startListening
,ok 135 discoveryActive should be false
,ok 136 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BD168E4F-9BC6-4456-A443-FA3AB554AE40", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BD168E4F-9BC6-4456-A443-FA3AB554AE40
,ok 137 discoveryActive should be false
ok 138 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 139 discoveryActive should be false
ok 140 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,ok 141 discoveryActive should be false
,ok 142 advertisingActive should be true
,ok 143 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-14 11:30:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-14 11:30:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-14 11:30:25 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-14 11:30:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-14 11:30:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 154 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-14 11:30:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 158 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:c2c000a3-5244-432d-84d6-7345bb615721 error: startListeningNotActive
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cTX2WgBAW6Y5tfnw60Bli0fYOeYwhlZT","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 159 Should only get called after multiConnect returned
,ok 160 SyncValue matches
,ok 161 Got right error
,ok 162 listeningPort is null
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"c2c000a3-5244-432d-84d6-7345bb615721","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"c2c000a3-5244-432d-84d6-7345bb615721","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:524E9F54-CD1C-416E-B1D3-D078378C9C68
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 165 No error on starting
,ok 166 Got null as expected
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dbfWOijG0HzItpADoGAD6RFnaj4A1l5R","error":"Illegal peerID","portNumber":null}'
,ok 167 Should only get called after multiConnect returned
,ok 168 SyncValue matches
,ok 169 Got right error
,ok 170 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-14 11:30:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 173 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:58EF5489-290E-4B0A-B0C7-0FCC0A38BD35
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 175 No error on starting
,ok 176 Got right error
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
[ThaliCore] BrowserManager.st,opListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:28 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 177 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 178 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","generation":0}]'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","generation":0}'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call disconnect with invalid peer id
,ok 179 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 180 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 181 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:cc864591-3338-4ce9-bfac-df97f528af3e
ok 182 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:29 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 183 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 184 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Get same port when trying to connect multiple times on iOS
,2017-07-14 11:30:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 185 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 186 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# initial peer discovery
,2017-07-14 11:30:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-14 11:30:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-14 11:30:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-14 11:30:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-14 11:30:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-14 11:30:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'listening 49998'
,ok 187 Should throw
,# teardown
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'listening 50000'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 initial connection state should be CONNECTED
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 189 final connection state should be DISCONNECTED
,# teardown
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'listening 50003'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 190 tried to connect to right port
,ok 191 failed due to refused connection
,ok 192 routerPortConnectionFailed is emitted
,# teardown
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'listening 50007'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 193 Send/recvd #1 should be equal length
,ok 194 Send/recvd #1 should be same
,ok 195 Send/recvd #2 should be equal length
,ok 196 Send/recvd #2 should be same
,ok 197 Should be exactly 2 client sockets
,# teardown
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'listening 50012'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 198 socket shouldn't close until after stream
,ok 199 incoming remains open
,# teardown
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-14 11:30:33, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'listening 50016'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should not have gotten an error
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 socket shouldn't close until after incoming
,ok 202 incoming is cleaned up
,# teardown
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'listening 50020'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 203 stream was closed
,ok 204 incoming should survive
,ok 205 mux should have no streams
,# teardown
,2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:35 - DEBUG createNativeListener: 'listening 50024'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 206 we should not have gotten an error
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 207 Buffers are identical
,2017-07-14 11:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 208 native server is nulled out
,ok 209 native server should be closed
,ok 210 incoming has been removed
,ok 211 Incoming should be done
,ok 212 The mux object should be closed
,ok 213 The mux stream should be closed
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:35 - DEBUG createNativeListener: 'listening 50028'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-14 11:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 214 native server is nulled out
,ok 215 native server should be closed
,ok 216 incoming has been removed
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'listening 50080'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 217 we should not have gotten an error
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 218 Buffers are identical
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 219 server should be fine
,ok 220 server should be open
,ok 221 incoming has been removed
,ok 222 The mux object should be closed
,ok 223 The mux stream should be closed
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'listening 50084'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 224 we should not have gotten an error
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 225 Buffers are identical
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 226 server should be fine
,ok 227 server should be open
,ok 228 incoming has been removed
,ok 229 The mux object should be closed
,ok 230 The mux stream should be closed
,# teardown
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 231 serversManager must not be null
ok 232 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 233 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-14 11:30:38 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:38 - DEBUG createNativeListener: 'listening 50087'
ok 234 port must be in range
,# teardown
,2017-07-14 11:30:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:38 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'listening 50088'
,ok 235 second start should return same port
,# teardown
,2017-07-14 11:30:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:39 - DEBUG createNativeListener: 'listening 50090'
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 236 we should be connected
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 237 now we are disconnected
,2017-07-14 11:30:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-14 11:30:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-14 11:30:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 238 Passed bogus id
,2017-07-14 11:30:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 239 Passed good id but bogus port
,2017-07-14 11:30:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 240 Passed right context
,ok 241 Right server
,ok 242 No error should be set
,ok 243 Retry should be false
,ok 244 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 50092
,ok 245 should be equal
,# teardown
,2017-07-14 11:30:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:910AB337-4ECA-404D-A728-DA5FDCBE0C94
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 246 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
2017-07-14 11:30:40 - INFO th,aliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}}),'
2017-07-14 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 247 Can call startListeningForAdvertisements without error
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","generation":0}'
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 364E65AB-A73B-46E1-BB05-C330DF77328F (syncValue: ettQgPADNeudyRxL4qPhQM5fErNxrnQn)'
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
,2017-07-14 11:30:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}'
,2017-07-14 11:30:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2DAB5366-D8ED-405B-840D-3F714804033E (syncValue: wYmgQKP2V0GyX6BG4b4M7YjqtMS4EMWk)'
,2017-07-14 11:30:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46
[ThaliCore] Advertiser: session connected Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
[ThaliCore] Advertiser: session connected Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,2017-07-14 11:30:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}'
,2017-07-14 11:30:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8A025A44-AD9A-48D7-A59F-2F0C9E83D78C (syncValue: S7xQTHozqRfDtMfEGjiyLNKygg2lEzG9)'
,2017-07-14 11:30:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
,[ThaliCore] Session.disconnect() peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50100
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"S7xQTHozqRfDtMfEGjiyLNKygg2lEzG9","error":null,"portNumber":50100}'
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'S7xQTHozqRfDtMfEGjiyLNKygg2lEzG9', error: 'null', listeningPort: '50100''
,2017-07-14 11:30:44 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'S7xQTHozqRfDtMfEGjiyLNKygg2lEzG9', originalSyncValue: 'ettQgPADNeudyRxL4qPhQM5fErNxrnQn''
2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Go,t multiConnectResolved -syncValue: 'S7xQTHozqRfDtMfEGjiyLNKygg2lEzG9', error: 'null', listeningPort: '50100''
2017-07-14 11:30:44 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'S7xQTHozqRfDtMfEGjiyLNKygg2lEzG9', orig,inalSyncValue: 'wYmgQKP2V0GyX6BG4b4M7YjqtMS4EMWk''
2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'S7xQTHozqRfDtMfEGjiyLNKygg2lEzG9', error: 'null', listeningPort: '50100''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: connecting -> connected
,ok 248 should be equal
,ok 249 (unnamed assert)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50102
[ThaliCore] Session.session(_:peer:didChange:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29 state: connecting -> connected
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wYmgQKP2V0GyX6BG4b4M7YjqtMS4EMWk","error":null,"portNumber":50102}'
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wYmgQKP2V0GyX6BG4b4M7YjqtMS4EMWk', error: 'null', listeningPort: '50102''
,2017-07-14 11:30:44 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'wYmgQKP2V0GyX6BG4b4M7YjqtMS4EMWk', originalSyncValue: 'ettQgPADNeudyRxL4qPhQM5fErNxrnQn''
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wYmgQKP2V0GyX6BG4b4M7YjqtMS4EMWk', error: 'null', listeningPort: '50102''
,ok 250 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: connected -> notConn,ected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50100
[ThaliCore] Advertiser: session notConnected Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
[ThaliCore] Session.disconnect() peer:8A025A44-AD9A,-48D7-A59F-2F0C9E83D78C:0
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] BrowserManager.disconnect peer:2DAB5366-D8ED-405B-840D-3F714804033E
[ThaliCore] TCPClient.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:,0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Browser: session notConnected Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50102
,[ThaliCore] Session.disconnect() peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
[ThaliCore] Session.disconnect() peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.deinit peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
2017-07-14 11:30:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple local http requests
,listening on 50104
,ok 251 should be equal
,ok 252 should be equal
,ok 253 should be equal
,# teardown
,2017-07-14 11:30:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:910AB337-4ECA-404D-A728-DA5FDCBE0C94
2017-07-14 1,1:30:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:30:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
ok 254 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 255 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.session(_:peer:didChange:) peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", genera,tion: 0)
2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ettQgPADNeudyRxL4qPhQM5fErNxrnQn","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:30:46 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'ettQgPADNeudyRxL4qPhQM5fErNxrnQn', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 364E65AB-A73B-46E1-BB05-C330DF77328F (syncValue: nThjsXbqlvIRS8recjvgH7QDmuRPFC56)'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nThjsXbqlvIRS8recjvgH7QDmuRPFC56","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nThjsXbqlvIRS8recjvgH7QDmuRPFC56', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46
[ThaliCore] Advertiser: session connected Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: notConnected -> connecting
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"pe,erIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":1}'
2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8A025A44-AD9A-48D7-A59F-2F0C9E83D78C (syncValue: fXbX9oRpAN57wflmybweG2yJrPAVinW6)'
2017-07-14 11:30:4,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
[ThaliCore] Advertiser: session connected Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29 state: notConnected -> connecting
7 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":1}'
,2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2DAB5366-D8ED-405B-840D-3F714804033E (syncValue: AVg8fFTo6tJdIj1UScWpysVsCIqUq6ZP)'
,2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:1
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50112
2017-07-14 11:30:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fXbX9oRpAN57wflmybweG2yJrPAVinW6",,"error":null,"portNumber":50112}'
2017-07-14 11:30:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fXbX9oRpAN57wflmybweG2yJrPAVinW6', error: 'null', listeningPort: '50112''
2017-07-14 11:30:50 - DEBUG thaliMobileNativeTestUt,ils: 'Got multiConnectResolved -syncValue: 'fXbX9oRpAN57wflmybweG2yJrPAVinW6', error: 'null', listeningPort: '50112''
2017-07-14 11:30:50 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'fXbX9oRpAN57wflmybweG2yJrPAVin,W,6', originalSyncValue: 'AVg8fFTo6tJdIj1UScWpysVsCIqUq6ZP''
,ok 256 should be equal
,ok 257 (unnamed assert)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29 state: connecting -> connected
[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:1 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50114
,2017-07-14 11:30:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AVg8fFTo6tJdIj1UScWpysVsCIqUq6ZP","error":null,"portNumber":50114}'
,2017-07-14 11:30:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AVg8fFTo6tJdIj1UScWpysVsCIqUq6ZP', error: 'null', listeningPort: '50114''
,ok 258 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50112
,[ThaliCore] Session.disconnect() peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserManager.disconnect peer:2DAB5366-D8ED-405B-840D-3F714804033E
[ThaliCore], BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50114
[ThaliCore] Session.disconnect() peer:2DAB5366-D8ED-405B-840D-3F714804033E:1
[ThaliCore] TCPListener.socketDidDisconnect(,_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78,C", generation: 1)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: connected -> ,notConnected
[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:1 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
,[ThaliCore] Browser: session notConnected Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
,[ThaliCore] Session.deinit peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
,2017-07-14 11:30:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startListeningForAdvertisements should fail if start not called
,ok 259 specific error should be returned
,# teardown
,ok 260 must be stopped
,# setup
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 261 specific error should be returned
,# teardown
,ok 262 must be stopped
,# setup
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'listening 50116'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 263 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 264 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 265 must be stopped
,# setup
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startListeningForAdvertisements many times
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'listening 50117'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:89D455FB-6813-423A-8B43-B61441BD7C48
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 266 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 267 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 268 must be stopped
,# setup
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'listening 50118'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "20374F07-5D21-447E-926E-15BD9BCFB411", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:20374F07-5D21-447E-926E-15BD9BCFB411
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 269 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "20374F07-5D21-447E-926E-15BD9BCFB411", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:20374F07-5D21-447E-926E-15BD9BCFB411
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 11:30:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 271 must be stopped
,# setup
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'listening 50121'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 273 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 274 must be stopped
,# setup
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can get the network status before starting
,ok 275 network status should have certain non-empty properties
,# teardown
,ok 276 must be stopped
,# setup
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# error returned with bad router
,2017-07-14 11:30:54 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 277 specific error expected
,# teardown
,ok 278 must be stopped
,# setup
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are started when we call start
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'listening 50122'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1DE466AC-E9BC-43D0-946F-4838751B4669
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AA594F33-2668-4D03-BA11-32D71DBE909C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:AA594F33-2668-4D03-BA11-32D71DBE909C
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 279 all connection succeed
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
2017-07-14 11:30:54 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}]'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native, layer [{"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":1}]'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2DAB5366-D,8ED-405B-840D-3F714804033E","generation":1}'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":1}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":1}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
,# setup
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'listening 50125'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:63ADEED7-403E-4CDF-86F8-C98AE6569F92
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC4F9162-07BB-4EFD-B8CD-D3EDBB2BF304", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EC4F9162-07BB-4EFD-B8CD-D3EDBB2BF304
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 281 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:1
2017-07-14 11:30:54 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-,405B-840D-3F714804033E", generation: 1)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWr,apper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}]'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed eve,nt with {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":1}]'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":1}'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native, layer [{"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":1}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":1}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeW,rapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitt,ing {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":1,"portNumber":null}'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8A025A44-AD9A-48D7-A59F,-2F0C9E83D78C","peerAvailable":true,"generation":1,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 282 must be stopped
,# setup
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are stopped when we call stop
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'listening 50127'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:357FA396-B4D8-46AE-B163-1DB573D4A47E
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.foundP,eerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CC067E1B-DEB5-42D7-B743-E38739A509F4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CC067E1B-DEB5-42D7-B743-E38739A509F4
2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:30:55 ,- INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType,":null}})'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper:, 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14, 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 is stopped after calling stop
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}]'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 284 connection should fail after stopping
,# teardown
,ok 285 must be stopped
,# setup
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is properly hooked up
,2017-07-14 11:30:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 286 must be stopped
,# setup
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is return error if we get called on iOS
,ok 287 error description matches
,# teardown
,ok 288 must be stopped
,# setup
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is properly hooked up
,2017-07-14 11:30:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 289 must be stopped
,# setup
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is return error if we get called on iOS
,ok 290 error description matches
,# teardown
,ok 291 must be stopped
,# setup
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure we actually call kill connections properly
,ok 292 IMPLEMENT ME!!!!!!
,# teardown
,ok 293 must be stopped
,# setup
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-14 11:30:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 294 must be stopped
,# setup
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-14 11:30:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 295 must be stopped
,# setup
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-14 11:30:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 296 must be stopped
,# setup
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-14 11:30:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 297 must be stopped
,# setup
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 298 NOT IMPLEMENTED # SKIP
,# teardown
,ok 299 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure bad PSK connections fail
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 300 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peer changes handled from a queue
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 301 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 302 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 303 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50130'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F733B3C1-B6F9-4C9C-9035-185CBB9557A1
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 304 discoveryActive matches
,ok 305 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 306 discoveryActive matches
ok 307 advertisingActive matches
,2017-07-14 11:31:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50131'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "02E8BC92-B4FD-457D-A1E2-CC5ACF8AA3CC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:02E8BC92-B4FD-457D-A1E2-CC5ACF8AA3CC
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 308 discoveryActive matches
,ok 309 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 310 discoveryActive matches
ok 311 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50133'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 must be stopped
,# setup
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50134'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:87DEFAF6-8400-4875-95F0-ED2423725483
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "15FBA89B-0799-48A9-85B4-88553B1753B0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:15FBA89B-0799-48A9-85B4-88553B1753B0
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
2017-07-14 11:31:01 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}]'
2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}'
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 313 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0)
2017-07-14 11:31:01 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation":0}]'
2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation":0}'
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 314 must be stopped
,# setup
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests between peers
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'listening 50136'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B79ED0FF-746F-4619-8CC2-79625CF85DCD
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:30EEEF58-6F93-47A9-AFF1-D262152011B0
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:31:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}]'
2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E",",generation":0}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","generation":0}]'
2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","generation":0}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47 (syncValue: VNexL2vy4XjJsAcnxt44XVjcUgvsJpDq)'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:31:03 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:31:03 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0)
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}]'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4DBF6215-1DC7-4E8A-956F-2B203C76E46B
[ThaliCore] Advertiser: session connected Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4DBF6215-1DC7-4E8A-956F-2B203C76E46B state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0 state: notConnected -> notConnected
,[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] Session.disconnect() peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0)
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VNexL2vy4XjJsAcnxt44XVjcUgvsJpDq","error":"Connection could not be established","portNumber":null}'
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VNexL2vy4XjJsAcnxt44XVjcUgvsJpDq', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 11:31:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 11:31:09 - DEBUG thaliMobileNat,iveTestUtils: 'We got a peer {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:31:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2DAB5366-D8ED-405B-840D-3F714804033E (syncValue: 4sEiJ0hfFYWK7LZo0BNNnveah8gommEH)'
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4sEiJ0hfFYWK7LZo0BNNnveah8gommEH","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4sEiJ0hfFYWK7LZo0BNNnveah8gommEH', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:31:09 - DEBUG thaliMobil,eNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D08813FF-67B9-418D-ADC2-3A899BCA976D (syncValue: iwyrr1xv96PsYzDmEAl7gu5dab9L1YYG)'
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0)
2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation":0}]'
2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation":0}'
,2017-07-14 11:31:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 11:31:09 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4DBF6215-1DC7-4E8A-956F-2B203C76E46B
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DBF6215-1DC7-4E8A-956F-2B203C76E46B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4DBF6215-1DC7-4E8A-956F-2B203C76E46B
[ThaliCore] Session.startOutputStream(with:) peer:4DBF6215-1DC7-4E8A-956F-2B203C76E46B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [2, 5, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50142
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iwyrr1xv96PsYzDmEAl7gu5dab9L1YYG","error":null,"portNumber":50142}'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iwyrr1xv96PsYzDmEAl7gu5dab9L1YYG', error: 'null', listeningPort: '50142''
,2017-07-14 11:31:12 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [2, 5, 11, 12, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:31:12 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:31:12 - DEBUG testUtils: 'Got end'
,ok 315 response body should match testData
,ok 316 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:13 [2, 5, 11, 12]
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DBF6215-1DC7-4E8A-956F-2B203C76E46B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:nil
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true,
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [2, 5, 11]
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4DBF6215-1DC7-4E8A-956F-2B203C76E46B
[ThaliCore] Advertise,rRelay.deinit
,[ThaliCore] Session.deinit peer:4DBF6215-1DC7-4E8A-956F-2B203C76E46B
,2017-07-14 11:31:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:D08813FF-67B9-418D-ADC2-3A899BCA976D
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50142
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
,# setup
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can still do HTTP requests between peers with coordinator
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'listening 50144'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:62DF7AE8-2B52-4E5D-9826-79DD2B8876B5
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4058EBCF-2389-4A80-8739-3BC964E93946
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0)
2017-07-14 11:31:13 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}]'
2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:31:13 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 117A1A18-8269-454A-B098-B1D2BC0CA55,7 (syncValue: yBSzta3ykHyHHHHTSEfn4S53YtjdvQBs)'
2017-07-14 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", ge,neration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:117A1A18-8269-,454A-B098-B1D2BC0CA557:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:49D2AE96-57F9-4114-BFBB-AC26386E4157:0
2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49D2AE96-57F9-4114-BFBB-AC26386E4157", generation: 0)
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","generation":0}]'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","generation":0}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0)
[ThaliCore] Session.disconnect() peer:117A1A18-826,9-454A-B098-B1D2BC0CA557:0
2017-07-14 11:31:17 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}]'
2017-07-14 11:31:,17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}'
,2017-07-14 11:31:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 11:31:17 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", genera,tion: 0)
2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yBSzta3ykHyHHHHTSEfn4S53YtjdvQBs","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:31:19 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'yBSzta3ykHyHHHHTSEfn4S53YtjdvQBs', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 11:31:19 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:31:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:117A1A18-8269-454A-B098-B1D2BC0CA557
2017-07-14 11:31:19 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-14 11:31:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 75A74F2C-36D7-4F68-A621-7E4E5356421E (syncValue: nDF0hJZHML982w6T8gZ6ttm8oo4TzMAA)'
,2017-07-14 11:31:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:82BB5CCD-7D08-4872-AE79-6F65FA9D0D0C
[ThaliCore] Advertiser: session connected Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:82BB5CCD-7D08-4872-AE79-6F65FA9D0D0C state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:82BB5CCD-7D08-4872-AE79-6F65FA9D0D0C
,[ThaliCore] Session.session(_:peer:didChange:) peer:82BB5CCD-7D08-4872-AE79-6F65FA9D0D0C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:82BB5CCD-7D08-4872-AE79-6F65FA9D0D0C
[ThaliCore] Session.startOutputStream(with:) peer:82BB5CCD-7D08-4872-AE79-6F65FA9D0D0C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [2, 5, 11, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50152
,2017-07-14 11:31:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nDF0hJZHML982w6T8gZ6ttm8oo4TzMAA","error":null,"portNumber":50152}'
,2017-07-14 11:31:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nDF0hJZHML982w6T8gZ6ttm8oo4TzMAA', error: 'null', listeningPort: '50152''
,2017-07-14 11:31:22 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [2, 5, 11, 14, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:31:22 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:31:22 - DEBUG testUtils: 'Got end'
,ok 318 response body should match testData
,ok 319 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:00AD4566-99CB-40F7-8BED-6FACD03A9D0E
[ThaliCore] Advertiser: session connected Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:00AD4566-99CB-40F7-8BED-6FACD03A9D0E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:00AD4566-99CB-40F7-8BED-6FACD03A9D0E
,[ThaliCore] Session.session(_:peer:didChange:) peer:00AD4566-99CB-40F7-8BED-6FACD03A9D0E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00AD4566-99CB-40F7-8BED-6FACD03A9D0E
,[ThaliCore] Session.startOutputStream(with:) peer:00AD4566-99CB-40F7-8BED-6FACD03A9D0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [2, 5, 11, 14, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:31:2,9 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-14 11:31:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:31:29 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 11:31:29 - DEBUG, makeIntoCloseAllServer: 'closeAll called on server'
,ok 320 must be stopped
[ThaliCore] BrowserManager.disconnect peer:75A74F2C-36D7-4F68-A621-7E4E5356421E
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50152
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] Session.session(_:peer:didChange:) peer:00AD4566-99CB-40F7-8BED-6FACD03A9D0E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] TCPClient.socketDidDisconnect(_,:withError:) disconnecting:true socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.deinit
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] Virt,ualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:16 [2, 5, 11, 14, 15]
[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] Session.disconnect() peer:00AD4566-99CB-40F7-8BED-6FACD03A9D0E
[ThaliCore] VirtualSocket.deinit vsID:14 [2, 5, 11, 15]
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] VirtualSocket.deinit vsID:15 [2, 5, 11]
,[ThaliCore] Session.disconnect() peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:82BB5CCD-7D08-4872-AE79-6F65FA9D0D0C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:00AD4566-99CB-40F7-8BED-6FACD03A9D0E
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# calls correct starts when network changes
,2017-07-14 11:31:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 321 must be stopped
,# setup
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:31:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# test to coordinate connection cut
,# teardown
,ok 322 must be stopped
,# setup
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests after connections are cut
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'listening 50156'
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C8990B9F-58FA-4A2E-AAB2-7242E6E86733
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:31:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:31:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation":0}]'
2017-07-14 11:31:32 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation":0}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 75A74F2C-36D7-4F68-A621-7E4E5356421E (syncValue: TvRy8LY51OczUja4nZRDss3kTNdt1W4I)'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A11FB974","generation":0}]'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A11FB974","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0
2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A1,1FB974","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
2017-07-14 11:31:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A11FB974","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A11FB974","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","generation":0}]'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","generation":0}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", genera,tion: 0)
2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TvRy8LY51OczUja4nZRDss3kTNdt1W4I","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:31:37 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'TvRy8LY51OczUja4nZRDss3kTNdt1W4I', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E89525DA-D2AA-454F-878F-E377A11FB974 (syncValue: 67Fa852wmxnXuEGVc3KWaqITKWfY4Euz)'
,2017-07-14 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50163
2017-07-14 11:31:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"67Fa852wmxnXuEGVc3KWaqITKWfY4Euz",,"error":null,"portNumber":50163}'
2017-07-14 11:31:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '67Fa852wmxnXuEGVc3KWaqITKWfY4Euz', error: 'null', listeningPort: '50163''
,2017-07-14 11:31:40 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [2, 5, 11, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:31:41 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:31:41 - DEBUG testUtils: 'Got end'
,ok 323 response body should match testData
,ok 324 must be started
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
2017-07-14 11:31:41 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation":0}]'
2017-07-14 11:31:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation":0}'
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 11:31:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:31:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:31:4,5 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-14 11:31:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:31:45 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 11:31:45 - DEBU,G makeIntoCloseAllServer: 'closeAll called on server'
,ok 325 must be stopped
[ThaliCore] BrowserManager.disconnect peer:E89525DA-D2AA-454F-878F-E377A11FB974
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50163
[Thali,Core] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] Session.disconnect() peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
[ThaliCore], VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [2, 5, 11]
,[ThaliCore] Session.session(_:peer:didChange:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
,# setup
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# will fail bad PSK connection between peers
,ok 326 FIX ME, PLEASE!!!
,# teardown
,ok 327 must be stopped
,# setup
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:47 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We provide notification when a listener dies and we recreate it
,2017-07-14 11:31:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 328 must be stopped
,# setup
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-14 11:31:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 329 must be stopped
,# setup
,ok 330 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 331 specific error should be returned
,# teardown
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A11FB974","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 332 error should be null
,ok 333 error should be null
,# setup
,ok 334 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 335 specific error should be returned
,# teardown
,ok 336 error should be null
,ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'listening 50165'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 339 error should be null
ok 340 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 341 error should be null
,ok 342 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 343 error should be null
,ok 344 error should be null
,# setup
,ok 345 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'listening 50166'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:454F43EB-C62F-498D-A8F3-E2037397D1B6
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 346 error should be null
,ok 347 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 348 error should be null
,ok 349 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 350 error should be null
,ok 351 error should be null
,# setup
,ok 352 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'listening 50167'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AA67B4D7-4DCE-4F38-A077-1368F3F54C64", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AA67B4D7-4DCE-4F38-A077-1368F3F54C64
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 353 error should be null
,ok 354 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AA67B4D7-4DCE-4F38-A077-1368F3F54C64", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:AA67B4D7-4DCE-4F38-A077-1368F3F54C64
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 355 error should be null
,ok 356 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 357 error should be null
,ok 358 error should be null
,# setup
,ok 359 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'listening 50170'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 360 error should be null
,ok 361 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 362 error should be null
,ok 363 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 364 error should be null
,ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-14 11:31:50 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 367 This should not cause wifi to fail
,ok 368 native router should be bad
,# teardown
,ok 369 error should be null
,ok 370 error should be null
,# setup
,ok 371 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'listening 50171'
,ok 372 first call should succeed
,ok 373 first call should succeed
,ok 374 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 375 error should be null
,ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-14 11:31:51 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 378 error should be null
,ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-14 11:31:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 381 error should be null
,ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-14 11:31:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e80f9d99-5523-416e-b1ab-ae495185956d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 384 should be called once
,ok 385 should not have been called more than once
,# teardown
,2017-07-14 11:31:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e80f9d99-5523-416e-b1ab-ae495185956d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 386 error should be null
,ok 387 error should be null
,# setup
,ok 388 ThaliMobile should be stopped
,# can get the network status
,ok 389 network status should have certain non-empty properties
,# teardown
,ok 390 error should be null
,ok 391 error should be null
,# setup
,ok 392 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 393 we have not added peer to the cache yet
,2017-07-14 11:31:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a2159685-e800-48d8-a692-322d199d1dcd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 394 peer should be available
,ok 395 cache contains native peer
,2017-07-14 11:31:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a2159685-e800-48d8-a692-322d199d1dcd","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 396 peer should be unavailable
,ok 397 peer has been removed from cache
,# teardown
,ok 398 error should be null
,ok 399 error should be null
,# setup
,ok 400 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 401 we have not added peer to the cache yet
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f8b149e1-1bab-4773-89cb-0c9d70b0d870","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 402 peer should be available
,ok 403 cache contains wifi peer
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f8b149e1-1bab-4773-89cb-0c9d70b0d870","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 404 peer should be unavailable
,ok 405 peer has been removed from cache
,# teardown
,ok 406 error should be null
,ok 407 error should be null
,# setup
,ok 408 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3437923a-7e00-456f-ac39-a6de38b45ec0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 409 first peer is available
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"07205580-d73c-4dab-82d0-66d08774822f","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 410 second peer is available
,ok 411 first and second peers are different
,# teardown
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3437923a-7e00-456f-ac39-a6de38b45ec0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"07205580-d73c-4dab-82d0-66d08774822f","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 412 error should be null
,ok 413 error should be null
,# setup
,ok 414 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 415 should not be in cache at start
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10baca79-2bc9-4a49-bfbe-898afc57d10a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 416 peer is available
,# teardown
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"10baca79-2bc9-4a49-bfbe-898afc57d10a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 417 error should be null
,ok 418 error should be null
,# setup
,ok 419 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-14 11:31:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 420 error should be null
,ok 421 error should be null
,# setup
,ok 422 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-14 11:31:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 423 error should be null
ok 424 error should be null
,# setup
,ok 425 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c6c918b-5c6a-4ef8-b007-b702687e812f","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 426 peer should be available
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c6c918b-5c6a-4ef8-b007-b702687e812f","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 427 peer should be available
,ok 428 should store correct generation
,# teardown
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6c6c918b-5c6a-4ef8-b007-b702687e812f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 429 error should be null
,ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-14 11:31:54 - DEBUG thaliMobileNativeWrapper: 'listening 50172'
2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6e1f37ad-dfbd-4fe4-8131-652abd5c2fe3","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 432 discovered correct peer
ok 433 got correct generation
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6e1f37ad-dfbd-4fe4-8131-652abd5c2fe3","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 434 discovered correct peer
,ok 435 got correct generation
,# teardown
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6e1f37ad-dfbd-4fe4-8131-652abd5c2fe3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-14 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-14 11:31:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 436 error should be null
,ok 437 error should be null
,# setup
,ok 438 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'listening 50173'
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7319e75d-93e7-4ff4-9312-a732b65dbc8a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 439 discovered available peer
,ok 440 peer is available
,# teardown
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7319e75d-93e7-4ff4-9312-a732b65dbc8a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 441 error should be null
,ok 442 error should be null
,# setup
,ok 443 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"23c4cf63-ef58-4a13-ac2b-4074c9adfadb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 444 peer should be available
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"23c4cf63-ef58-4a13-ac2b-4074c9adfadb","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 445 peer should be unavailable
,ok 446 should be removed from cache
,# teardown
,ok 447 error should be null
,ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'listening 50174'
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"81d89e3e-e5f6-4623-8f54-0f2037bacb93","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 450 first peer is expected to be available
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"41f5df8d-b9d2-4e48-accb-88619ae06b4b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 451 second peer is expected to be available
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"41f5df8d-b9d2-4e48-accb-88619ae06b4b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 452 peer became unavailable
,ok 453 it was wifi peer
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"41f5df8d-b9d2-4e48-accb-88619ae06b4b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 454 we found peer again
,ok 455 it was wifi peer
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"41f5df8d-b9d2-4e48-accb-88619ae06b4b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 456 peer became unavailable
,ok 457 it was wifi peer
,# teardown
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"81d89e3e-e5f6-4623-8f54-0f2037bacb93","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 458 error should be null
,ok 459 error should be null
,# setup
,ok 460 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-14 11:31:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 461 error should be null
ok 462 error should be null
,# setup
,ok 463 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-14 11:31:56 - DEBUG thaliMobileNativeWrapper: 'listening 50175'
,2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"802d4da1-fad2-48cc-af33-e4992e9b205e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 464 first peer is expected to be available
,2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"55afeba6-53f3-4f40-9f48-de0c8aaffdec","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 465 second peer is expected to be available
,2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"802d4da1-fad2-48cc-af33-e4992e9b205e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 466 peer became unavailable
,2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"55afeba6-53f3-4f40-9f48-de0c8aaffdec","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 467 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 468 error should be null
,ok 469 error should be null
,# setup
,ok 470 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-14 11:31:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-14 11:31:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 474 error should be null
ok 475 error should be null
,# setup
,ok 476 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1883a8d0-d9ee-4318-9457-54bfc36408b1","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 477 peer discovered ,first time does not have new address
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1883a8d0-d9ee-4318-9457-54bfc36408b1","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 478 address has not been changed
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1883a8d0-d9ee-4318-9457-54bfc36408b1","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 479 new port handled correctly
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1883a8d0-d9ee-4318-9457-54bfc36408b1","connectionType":"tcp","peerAvailable":tru,e,,"generation":20,"newAddressPort":true}'
ok 480 new host handled correctly
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1883a8d0-d9ee-4318-9457-54bfc36408b1","connectionType":"tcp","peerAva,ilable":false,"generation":20,"newAddressPort":null}'
ok 481 newAddressPort is null for unavailable peers
,# teardown
,ok 482 error should be null
ok 483 error should be null
,# setup
,ok 484 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-14 11:31:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 485 error should be null
,ok 486 error should be null
,# setup
,ok 487 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 488 NOT IMPLEMENTED # SKIP
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-14 11:31:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 495 should be equal
,# teardown
,ok 496 error should be null
ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-14 11:31:59 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 contains expected properties
ok 503 the same hostAddress
ok 504 the same portNumber
,# teardown
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 505 error should be null
ok 506 error should be null
,# setup
,ok 507 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 508 contains expected properties
ok 509 the same hos,tAddress
ok 510 the same portNumber
,# teardown
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 511 error should be null
ok 512 error should be null
,# setup
,ok 513 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 50176'
,2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"87078f46-0957-4154-b17c-8b99e448c55e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 514 Got specific error message
,# teardown
,2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"87078f46-0957-4154-b17c-8b99e448c55e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 515 error should be null
,ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 50177'
,2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bab9e202-cd5f-4b44-b29a-0030ebd29b19","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:bab9e202-cd5f-4b44-b29a-0030ebd29b19
,ok 518 native wrapper `disconnect` called once
,ok 519 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bab9e202-cd5f-4b44-b29a-0030ebd29b19","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 520 error should be null
,ok 521 error should be null
,# setup
,ok 522 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-14 11:32:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 523 error should be null
,ok 524 error should be null
,# setup
,ok 525 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 526 error should be null
,ok 527 error should be null
,# setup
,ok 528 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 529 error should be null
,ok 530 error should be null
,# setup
,ok 531 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 532 error should be null
,ok 533 error should be null
,# setup
,ok 534 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 535 error should be null
,ok 536 error should be null
,# setup
,ok 537 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-14 11:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 538 error should be null
,ok 539 error should be null
,# setup
,ok 540 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-14 11:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 541 error should be null
,ok 542 error should be null
,# setup
,ok 543 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'listening 50178'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:837141F7-ABD4-4956-B07D-220D5A08D285
,[ThaliCore] Browser.startListening
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0fd54dd8-5fc1-46c7-904d-189ee2fd746e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 544 Peer availabilities has one entry for our connection type
,2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a664b844-9b0d-48ca-a665-fb2d7d4e355b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 545 Peer availabilities has one entry for our connection type
,2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0fd54dd8-5fc1-46c7-904d-189ee2fd746e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a664b844-9b0d-48ca-a665-fb2d7d4e355b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:32:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-14 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 546 No peers
,ok 547 No peers
,ok 548 No peers
,# teardown
,ok 549 error should be null
,ok 550 error should be null
,# setup
,ok 551 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-14 11:32:04 - DEBUG thaliMobileNativeWrapper: 'listening 50179'
,2017-07-14 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f27a2ecc-93af-45cb-aa43-9d6dda761f09","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 552 1
,ok 553 2
,2017-07-14 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3f3cb787-9a5c-45c5-991f-4c2567658b5f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-14 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f27a2ecc-93af-45cb-aa43-9d6dda761f09","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14, 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3f3cb787-9a5c-45c5-991f-4c2567658b5f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-14 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 554 error should be null
,ok 555 error should be null
,# setup
,ok 556 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-14 11:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 557 error should be null
,ok 558 error should be null
,# setup
,ok 559 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 50180'
,ok 560 error should be null
,ok 561 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D8018271D03", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:994F4DE1-7A0E-410E-9D9D-4D8018271D03
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 562 error should be null
,ok 563 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2
,[ThaliCore] Browser.startListening
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 564 error should be null
,ok 565 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D8018271D03", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:42877076-2AF7-4818-A925-8E37D50E743E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "42877076-2AF7-4818-A925-8E37D50E743E", generation: 0)
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"42877076-2AF7-4818-A925-8E37D50E743E","generation":0}]'
2017-07-14 11:32:06 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"42877076-2AF7-4818-A925-8E37D50E743E","generation":0}'
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"42877076-2AF7-4818-A925-8E37D50E743E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"42877076-2AF7-4818-A925-8E37D50E743E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 42877076-2AF7-4818-A925-8E37D50E743E (syncValue: 0)'
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "42877076-2AF7-4818-A925-8E37D50E743E", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42877076-2AF7-4818-A925-8E37D50E743E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794
[ThaliCore] Advertiser: session connected Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D8018271D03", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "780F3D92-A26A-44CD-934D-636A0E30EC8B", generation: 0)
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"780F3D92-A26A-44CD-934D-636A0E30EC8B","generation":0}]'
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"780F3D92-A26A-44CD-934D-636A0E30EC8B","generation":0}'
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"780F3D92-A26A-44CD-934D-636A0E30EC8B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"780F3D92-A26A-44CD-934D-636A0E30EC8B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "42877076-2AF7-4818-A925-8E37D50E743E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50183
2017-07-14 11:32:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":50183,}'
,2017-07-14 11:32:08 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 780F3D92-A26A-44CD-934D-636A0E30EC8B (syncValue: 1)'
2017-07-14 11:32:08 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:completion:) Peer(uuid: "780F3D92-A26A-44CD-934D-636A0E30EC8B", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "780F3D92-A26A-44CD-934D-636A0E30EC8B", generation: 0)
[ThaliCo,re] Session.init(session:identifier:connected:notConnected:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794
[ThaliCore] Session.startOutputStream(with:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [2, 5, 11, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [2, 5, 11, 18, 19]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:32:10 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:32:10 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7
[ThaliCore] Advertiser: session connected Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D8018271D03", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "780F3D92-A26A-44CD-934D-636A0E30EC8B", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50189
,2017-07-14 11:32:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":50189}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [2, 5, 11, 18, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:32:11 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:32:11 - DEBUG testUtils: 'Got end'
,ok 566 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7
,[ThaliCore] Session.session(_:peer:didChange:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7
[ThaliCore] Session.startOutputStream(with:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,1 [2, 5, 11, 18, 19, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 11:32:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"42877076-2AF7-4818-A925-8E37D50E743E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:32:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"780F3D92-A26A-44CD-934D-636A0E30EC8B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:32:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-14 11:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsync,SocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler dis,connecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] Vi,rtualSocket.closeStreams() vsID:21
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [2, 5, 11, 19, 20, 21]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [2, 5, 11, 19, 20]
,ok 567 error should be null
ok 568 error should be null
,# setup
,ok 569 ThaliMobile should be stopped
,# test for data corruption
,2017-07-14 11:32:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:20 [2, 5, 11, 19]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [2, 5, 11]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# teardown
,ok 570 error should be null
,ok 571 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 572 getPeerIdentifier
ok 573 getConnectionType
ok 574 getActionType
ok 575 getActionState
ok 576 getPskIdentity
ok 577 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 578 initial state
ok 579 after start
2017-07-14 11:32:18 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 580 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 581 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-14 11:32:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 582 clean kill
,ok 583 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 584 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 585 forever agent should have it's own destroy method
,ok 586 agent's destroy should be called
,ok 587 agent's destroy should not be called again
,ok 588 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 589 Entry counter must be 1
,ok 590 Entry exists
,ok 591 Size must be 1
,ok 592 Entry counter must be 2
,ok 593 Entry exists
,ok 594 Size must be 2
,ok 595 Entry counter must be 1
,ok 596 Entry exists
,ok 597 Size must be 3
,ok 598 Entry counter must be 2
,ok 599 Entry exists
,ok 600 Size must be 4
,ok 601 Entry 1_1 should not be found
,ok 602 Entry 1_1 does not exist
,ok 603 Size must be 3
,ok 604 Entry 1_2 should not be found
,ok 605 Entry 1_2 does not exist
,ok 606 Size must be 2
,ok 607 should be equal
,ok 608 Entry 2_1 should not be found
,ok 609 Entry 2_2 should not be found
,ok 610 Entry 2_1 does not exist
,ok 611 Entry 2_2 does not exist
,ok 612 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 613 Size must be100
,ok 614 Entries between 20 and MAXSIZE + 20 should exist
,ok 615 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 616 Entries between 6 and MAXSIZE + 4 should exist
,ok 617 Size should be MAXSIZE
,ok 618 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 619 WAITING state entry should not be removed
,ok 620 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 621 Size should be MAXSIZE
,ok 622 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 623 Kill should be called once
,ok 624 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 625 is an agent
,ok 626 enqueue is fine
,ok 627 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 628 is an agent
,ok 629 first enqueue is fine
,ok 630 is an agent
,ok 631 second enqueue is fine
,ok 632 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 633 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 634 is an agent
,ok 635 good enqueue
,ok 636 Identity should match
,2017-07-14 11:32:24 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:32:24 - DEBUG testUtils: 'Got end'
,ok 637 Got expected response
,ok 638 Got psk call back
,# teardown
,2017-07-14 11:32:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 639 is an agent
ok 640 enqueue worked
ok 641 is an agent
ok 642 enqueue 2 worked
,ok 643 enqueue is not available when stopped
,ok 644 start action is killed
,ok 645 killed action is still killed
,ok 646 enqueued action when stopped is killed
,ok 647 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 648 good start
,ok 649 good enqueue
,ok 650 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 651 null arg
,ok 652 wrong arg type
,ok 653 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 654 good enqueue
ok 655 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 656 good enqueue
ok 657 2nd good enqueue
ok 658 we are in the pool
,ok 659 We are out of the pool
ok 660 Action was killed
ok 661 The original kill was called too
ok 662 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 663 good enqueue
,ok 664 first kill
,ok 665 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 666 1st good enqueue
,ok 667 2nd good enqueue
,ok 668 1st action is in the pool
,ok 669 2nd action is in the pool
,ok 670 1st action is out of the pool
,ok 671 2st action is out of the pool
,ok 672 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 673 Got right error
,ok 674 Start should not be called
,ok 675 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-14 11:32:27 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 676 Got right error
,ok 677 Start should not be called
,ok 678 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 679 Got null
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 680 is an agent
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 681 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 682 Got Null
,ok 683 Got another null
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 684 is an agent
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 685 is an agent
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 686 Action 1 killed at least once
,ok 687 Action 1 went first
,ok 688 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 689 should have gotten null
2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 690 Should have stopped nicely
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 691 Still looking for null
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 692 Yup, another null
,ok 693 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 694 Null 1
,ok 695 (unnamed assert)
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 696 is an agent
,ok 697 Null 3
,ok 698 Replication not yet called
,ok 699 Notification 2 not yet called
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 700 is an agent
,ok 701 Notification went first
,ok 702 Notification 2 not called yet
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 703 is an agent
,ok 704 Notification finished
,ok 705 Replication finished
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 706 is an agent
,ok 707 First does not throw
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 708 is an agent
,ok 709 Second does not throw
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 710 is an agent
,ok 711 first ok
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 712 is an agent
,ok 713 second ok
,ok 714 third ok
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-14 11:32:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-14 11:32:31 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 715 peerIdentifier should match
,ok 716 generation should match
,ok 717 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 718 good beacon
,ok 719 good preAmble
,ok 720 public keys match!
,ok 721 must return null after successful call
,ok 722 Once start returns the action should be in KILLED state
,# teardown
,2017-07-14 11:32:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 723 Response should be HTTP_BAD_RESPONSE
,ok 724 must return null after successful call
,# teardown
,2017-07-14 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 725 Response should be NETWORK_PROBLEM
ok 726 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-14 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 727 Resolution should be BAD_PEER
,ok 728 correct error message
,# teardown
,2017-07-14 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 729 Call start once
,ok 730 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 731 must return null after successful call.
,# teardown
,2017-07-14 11:32:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 732 Should be Killed
,ok 733 Start after killed
,# teardown
,2017-07-14 11:32:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 734 Should be KILLED
,ok 735 must return null after successful kill
,# teardown
,2017-07-14 11:32:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 736 Should be KILLED
ok 737 must return null after successful kill
,# teardown
,2017-07-14 11:32:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 738 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 739 must return null after successful call
,# teardown
,2017-07-14 11:32:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-14 11:32:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 740 Should be NETWORK_PROBLEM caused closing server socket
,ok 741 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 742 Should be NETWORK_PROBLEM caused closing client socket
,ok 743 Should be Could not establish TCP connection
,# teardown
,2017-07-14 11:32:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 744 publicKeysToNotify cannot be null
,ok 745 ecdh for local device cannot be null
,ok 746 milliseconds cannot be less than 0
,ok 747 milliseconds cannot be 0
,ok 748 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 749 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 750 should be equal
ok 751 should be equal
,ok 752 (unnamed assert)
,ok 753 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 754 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 755 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 756 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 757 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 758 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 759 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 760 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 761 should be equal
,ok 762 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 763 should be equal
,ok 764 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 765 right number of calls to address book
ok 766 good preAmble
,ok 767 good unencryptedKeyId
,ok 768 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 769 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 770 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 771 Matching numbers
,ok 772 We have an entry!
,ok 773 keys match
,ok 774 secrets match
,ok 775 We have an entry!
,ok 776 keys match
,ok 777 secrets match
,ok 778 We have an entry!
ok 779 keys match
,ok 780 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 781 Streams have same length
,ok 782 matching size
,ok 783 keys match
,ok 784 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 785 should be equal
,ok 786 peerDictionalty contains 2 peers
,ok 787 bluetooth peer's notification has correct connection type
,ok 788 tcp peer's notification has correct connection type
,2017-07-14 11:32:51 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-14 11:32:51 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-14 11:32:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 789 notification peer dictionary contains exactly 1 peer
,2017-07-14 11:32:52 - WARN thaliNotificationClient: 'peer is not available'
,ok 790 notification peer dictionary does not contain any peers
,2017-07-14 11:32:52 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-14 11:32:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 791 entry exists
,ok 792 entry is resolved
,# teardown
,2017-07-14 11:32:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 793 Action should be KILLED
,ok 794 Peer state should be RESOLVED
,# teardown
,2017-07-14 11:32:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 795 hostAddress must match
,ok 796 portNumber must match
,ok 797 suggestedTCPTimeout must match
,ok 798 connectionType must match
,ok 799 peerIDs must match
,# teardown
,2017-07-14 11:32:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 800 Correct error
,# teardown
,2017-07-14 11:32:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 801 hostAddress must match
,ok 802 portNumber must match
,ok 803 suggestedTCPTimeout must match
,ok 804 connectionType must match
,ok 805 peerIds must match
,# teardown
,2017-07-14 11:32:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-14 11:32:55 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 806 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 11:32:55 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 807 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 11:32:56 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 808 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 11:32:56 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 809 action should be resolved with NETWORK_PROBLEM error
,ok 810 correct number of requests
,ok 811 correct number of failures
,ok 812 correct final peer state
,# teardown
,2017-07-14 11:32:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-14 11:32:59 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 11:32:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 813 peerDictionary should become empty
,# teardown
,2017-07-14 11:32:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-14 11:32:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 814 failed with expected error
,ok 815 peer state should be RESOLVED
,# teardown
,2017-07-14 11:32:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-14 11:32:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 816 First action failed
,ok 817 second action killed
,# teardown
,2017-07-14 11:33:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 818 secrets are equal
,ok 819 Public key matches with the server key
,ok 820 hostAddress must match
,ok 821 portNumber must match
,ok 822 suggestedTCPTimeout must match
,ok 823 connectionType must match
,# teardown
,2017-07-14 11:33:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 824 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 825 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 826 All entries should be expired after 1 second
# teardown
,2017-07-14 11:33:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 827 All keys need to be available in the cache
,ok 828 All entries should be expired after 1 second
# teardown
,2017-07-14 11:33:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 829 Size of the cache should be 2
,ok 830 Cache doesn't contain dictionary1
,ok 831 Size of the cache should be 1
ok 832 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-14 11:33:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 833 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 834 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-14 11:33:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 835 StartUpdateAdvertisingAndListening should not be called
,ok 836 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 837 no error
,ok 838 should be 204
,# teardown
,2017-07-14 11:33:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 839 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-14 11:33:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 840 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-14 11:33:08 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-14 11:33:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-14 11:34:08 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get same port when trying to connect multiple times on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Pass an empty parameter to ThaliNotificationServer.start, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/D565EA4D-88E0,-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/blue,bird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-07-14 11:3,4:08 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-14 11:34:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:44:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:44:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-4,9D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D,6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D565EA4D-88E0-49D6-B96C-E31656BC1C1E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
