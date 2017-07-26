#### Test 1322832571374948_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1322832571374948/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/87EAC7D8-63E4-42E0-BC98-73D09EEA70FA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/87EAC7D8-63E4-42E0-BC98-73D09EEA70FA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1322832571374948/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1322832571374948/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62466"
,(lldb)     command script import "/tmp/87EAC7D8-63E4-42E0-BC98-73D09EEA70FA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
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
,2017-07-26 15:24:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:24:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:24:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:24:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:24:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:24:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:24:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5191276D-2366-4790-B4,4E-D6239ECDB2A3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5191276D-2366-4790-B44E-D6239ECDB2A3
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B2539F41-67DF-4D39-A266-319C2B1422C2
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3003922D-3FB7-4286-9784-D1FCB6E0B4CA
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "483FCE0D-FE8D-4AC9-9423-588DEC54AC31", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:483FCE0D-FE8D-4AC9-9423-588DEC54AC31
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:483FCE0D-FE8D-4AC9-9423-588DEC54AC31:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "483FCE0D-FE8D-4AC9-9423-588DEC54AC31", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-26 15:24:23 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  1.498769998550415
,2017-07-26 15:24:23 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-07-26 15:24:23 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:483FCE0D-FE8D-4AC9-9423-588DEC54AC31:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "483FCE0D-FE8D-4AC9-9423-588DEC54AC31", generation: 0)
,2017-07-26 15:24:27 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-26 15:24:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-26 15:24:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-26 15:24:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-26 15:24:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-26 15:24:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-26 15:24:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-26 15:24:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-26 15:24:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-26 15:24:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-26 15:24:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-26 15:24:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-26 15:24:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-26 15:24:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-26 15:24:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-26 15:24:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-26 15:24:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-26 15:24:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-26 15:24:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-26 15:24:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-26 15:24:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-26 15:24:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-26 15:24:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-26 15:24:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-26 15:24:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-26 15:24:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-26 15:24:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-26 15:24:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-26 15:24:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-26 15:24:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-26 15:24:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-26 15:24:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-26 15:24:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-26 15:24:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-26 15:24:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-26 15:24:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-26 15:24:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-26 15:24:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-26 15:24:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-26 15:24:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-26 15:24:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-26 15:24:31 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-26 15:24:31 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-26 15:24:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:25:09 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-26 15:25:09 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-26 15:25:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-26 15:25:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-26 15:25:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-26 15:25:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-26 15:25:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-26 15:25:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-26 15:25:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-26 15:25:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,ok 8 should be equal
,ok 9 should be equal
,ok 10 should be equal
,ok 11 should be equal
,ok 12 should be equal
,ok 13 should be equal
,ok 14 should be equal
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
,ok 32 fourth
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
,2017-07-26 15:25:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-26 15:25:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-26 15:25:42 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-26 15:25:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-26 15:25:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:182841DE-3C04-4BAC-97A5-4DBEE33C4B5F
[ThaliCore] Browser.startListening
2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-26 15:25:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:51 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C6CDCA3A-5750-46E1-B4C4-4B6D50957896
[ThaliCore] Browser.startListening
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-26 15:25:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-2,6, 15:25:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",networkType":null}})'
2017-07-26 15:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9B910831-57A9-40E4-B582-3963AE3A6039", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9B910831-57A9-40E4-B582-3963AE3A6039
2017-07-26 1,5:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising(,)
[ThaliCore] Advertiser.stopAdvertising() peerID:9B910831-57A9-40E4-B582-3963AE3A6039
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:53, - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD5E10B1-15B5-41B2-B1F3-32F4F4FD1166", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FD5E10B1-15B5-41B2-B1F3-32F4F4FD1166
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD5E10B1-15B5-41B2-B1F3-32F4F4FD1166", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:FD5E10B1-15B5-41B2-B1F3-32F4F4FD1166
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:25:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FD5E10B1-15B5-41B2-B1F3-32F4F4FD1166
[ThaliCore] Advertiser.stopAdvertising() peerID:FD5E10B1-15B5-41B2-B1F3-32F4F4FD1166,
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e,).'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "65BB0631-4C8E-48D5-9C63-E15CC7BCBCC0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:65BB0631-4C8E-48D5-9C63-E15CC7BCBCC0
2017-07-26 1,5:25:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:25:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A4519D6E-4771-4022-969D-85DB87F283C5
[ThaliCore] Browser.startListen,ing
2017-07-26 15:25:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:25:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true,}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisin,gStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:65BB0631-4C8E-48D5-9C63-E15CC7BCBCC0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65BB0631-4C8E-48D5-9C63-E15CC7BCBCC0", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E0E1C65-B1BC-4465-8138-E2F4FF7F1002:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E0E1C65-B1BC-4465-8138-E2F4FF7F1002", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) f,ound peer:7045561F-3AC7-42B2-AAA8-794CD97CD393:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7045561F-3AC7-42B2-AAA8-794CD97CD393", generation: 0)
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:25:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:65BB0631-4C8E-48D5-9C63-E15CC7BCBCC0
2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:233EEF45-D37B-4C1F-B455-6684C2646D24
2017-07-26 1,5:26:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C6CA495E-2E99-4FCC-AD24-3DAD01AF2F76
[ThaliCore] Browser.startListe,ning
2017-07-26 15:26:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:26:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:26:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
2017-07-26 15:26:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1972DBD3-7860-483F-83A6-386F04A64800","generation":0}'
2017-07-26 15:26:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1972DBD3-7860-483F-83A6-386F04A64800, (syncValue: DGwBbgJyCeOuAhZSTGd7C78TibIjBQM7)'
,2017-07-26 15:26:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:961C12C5-E0D8-4DB9-9E5B-2FF9B952B065
[ThaliCore] Advertiser: session connected Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:961C12C5-E0D8-4DB9-9E5B-2FF9B952B065 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
2017-07-26 15:26:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"81834FD2-2B19-4DA1-8940-C11D8697ADB7","generation":0}'
2017-07-26 15:26:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:05 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62321
,2017-07-26 15:26:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DGwBbgJyCeOuAhZSTGd7C78TibIjBQM7","error":null,"portNumber":62321}'
,2017-07-26 15:26:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DGwBbgJyCeOuAhZSTGd7C78TibIjBQM7', error: 'null', listeningPort: '62321''
,2017-07-26 15:26:07 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:961C12C5-E0D8-4DB9-9E5B-2FF9B952B065
,[ThaliCore] Session.session(_:peer:didChange:) peer:961C12C5-E0D8-4DB9-9E5B-2FF9B952B065 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:961C12C5-E0D8-4DB9-9E5B-2FF9B952B065 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:961C12C5-E0D8-4DB9-9E5B-2FF9B952B065
[ThaliCore] Advert,iserRelay.deinit
,2017-07-26 15:26:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 ,15:26:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-26 15:26:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:233EEF45-D37B-4C1F-B455-6,684C2646D24
2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:26:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:1972DBD3-7860-483F-83A6-386F04A64800
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62321
[ThaliCore] Session.disconnect() p,eer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] Session.deinit peer:961C12C5-E0D8-4DB9-9E5B-2FF9B952B065
,[ThaliCore] BrowserRelay.deinit
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:26:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A
2017-07-26 1,5:26:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:26726993-A74D-48FD-BA87-4EA1294BD300
[ThaliCore] Browser.startListening
2017-07-26 15:26:09 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:26:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListe,ningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"81834FD2-2B19-4DA1-8940-C11D8697ADB7","generation":0}'
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 81834FD2-2B19-4DA1-8940-C11D8697ADB7 (syncValue: hjctqOHlboxRv43RJmhfwdMfI2Tvjzoq)'
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81,834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1972DBD3-7860-483F-83A6-386F04A64800","generation":0}'
2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CC3FF4E7-6553-4363-AEA7-645E14A53DDD","generation":0}'
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
,2017-07-26 15:26:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"96F9B2E1-4E94-4042-B264-425C9D00CBDB","generation":0}'
,2017-07-26 15:26:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:68DB431D-089D-4A20-87E4-881769AEE578
[ThaliCore] Advertiser: session connected Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:68DB431D-089D-4A20-87E4-881769AEE578 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EAFC77EB-9012-4E06-A073-32941282816D
[ThaliCore] Advertiser: session connected Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EAFC77EB-9012-4E06-A073-32941282816D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7 error: max retries exceeded
,2017-07-26 15:26:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hjctqOHlboxRv43RJmhfwdMfI2Tvjzoq","error":"Connection could not be established","portNumber":null}'
,2017-07-26 15:26:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hjctqOHlboxRv43RJmhfwdMfI2Tvjzoq', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-26 15:26:21 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-26 15:26:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CC3FF4E7-6553-4363-AEA7-645E14A53DDD (syncValue: 1LsZ7aO2xqMnrDrSrYUr3mIwTVYqDEnx)'
,2017-07-26 15:26:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:26:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:68DB431D-089D-4A20-87E4-881769AEE578
,[ThaliCore] Session.session(_:peer:didChange:) peer:68DB431D-089D-4A20-87E4-881769AEE578 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68DB431D-089D-4A20-87E4-881769AEE578
[ThaliCore] Session.startOutputStream(with:) peer:68DB431D-089D-4A20-87E4-881769AEE578
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EAFC77EB-9012-4E06-A073-32941282816D
,[ThaliCore] Session.session(_:peer:didChange:) peer:EAFC77EB-9012-4E06-A073-32941282816D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EAFC77EB-9012-4E06-A073-32941282816D
,[ThaliCore] Session.startOutputStream(with:) peer:EAFC77EB-9012-4E06-A073-32941282816D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client discon,nected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62330
2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1LsZ7aO2xqMnrDrSrYUr3mIwTVYqDEnx","error":null,"portN,umber":62330}'
2017-07-26 15:26:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1LsZ7aO2xqMnrDrSrYUr3mIwTVYqDEnx', error: 'null', listeningPort: '62330''
,Connecting to the localhost:62330
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
,Connected to the localhost:62330
,2017-07-26 15:26:24 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-26 15:26:24 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 88 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 []
,# teardown
,2017-07-26 15:26:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:26:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-26 15:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62330
[ThaliCore] Session.disconnect() p,eer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EAFC77EB-9012-4E06-A073-32941282816D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:EAFC77EB-9012-4E06-A073-32941282816D
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:68DB431D-089D-4A20-87E4-881769AEE578 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
,[ThaliCore] Session.deinit peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:26:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] Session.deinit peer:EAFC77EB-9012-4E06-A073-32941282816D
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4E65AFCB-31AE-4C2A-AB9E-05D327D66222
2017-07-26 1,5:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C0524482-9D20-4396-9724-B784620F79E6
[ThaliCore] Browser.startListe,ning
2017-07-26 15:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:26:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisi,ngStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
2017-07-26 15:26:26 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CC3FF4E7-6553-4363-AEA7-645E14A53DDD","generation":0}'
2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CC3FF4E7-6553-4363-AEA7-645E14A53DDD, (syncValue: lhUkDRhXuucwil5MsvWIX6BJHMr2CqKg)'
2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A,53DDD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
2017-07-26 15:26:26, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"96F9B2E1-4E94-4042-B264-425C9D00CBDB","generation":0}'
2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CEA74DD1-9E19-42C5-827A-AEC245524BBC","generation":0}'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"426C00EC-1CE1-4DA1-851F-9CDEFAD2043E","generation":0}'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CC,3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,C3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CC,3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,C3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CC,3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,C3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-26 15:26:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lhUkDRhXuucwil5MsvWIX6BJHMr2CqKg","error":"Peer is unavailable",,"portNumber":null}'
2017-07-26 15:26:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lhUkDRhXuucwil5MsvWIX6BJHMr2CqKg', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-26 15:26:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-26 15:26:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 96F9B2E1-4E94-4042-B264-425C9D00CBDB (syncValue: b25nW0NtlH3ItgziZJAFnCp,1RYAF6dgy)'
2017-07-26 15:26:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:96F9B2E1-4E94-4042-B264-425C9,D00CBDB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:26:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:96,F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,6F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:96,F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,6F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:96,F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,6F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-26 15:26:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b25nW0NtlH3ItgziZJAFnCp1RYAF6dgy","error":"Peer is unavailable",,"portNumber":null}'
2017-07-26 15:26:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'b25nW0NtlH3ItgziZJAFnCp1RYAF6dgy', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-26 15:26:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-26 15:26:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CEA74DD1-9E19-42C5-827A-AEC245524BBC (syncValue: 1ifpegBv6lKlHSAFXnDXqle,ukOshJibR)'
2017-07-26 15:26:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CEA74DD1-9E19-42C5-827A-AEC24,5524BBC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:26:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62344
2017-07-26 15:26:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1ifpegBv6lKlHSAFXnDXqleukOshJibR",,"error":null,"portNumber":62344}'
2017-07-26 15:26:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1ifpegBv6lKlHSAFXnDXqleukOshJibR', error: 'null', listeningPort: '62344''
,Connecting to the localhost:62344
Connecting to the localhost:62344
Connecting to the localhost:62344
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
,Connected to the localhost:62344
[ThaliCore] Session.startOutputStream(with:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
Connected to the localhost:62344
Connected to the localhost:62344
,ok 91 correct string length
,2017-07-26 15:26:45 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-26 15:26:45 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
ok 93 correct string length
2017-07-26 15:26:45 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
2017-07-26 15:26:45 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-26 15:26:45 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-26 15:26:45 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [4, 6]
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 96 got the same data back
,# teardown
,2017-07-26 15:26:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [4]
2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:2,6:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"netwo,rkType":null}})'
2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4E65AFCB-31AE-4C2A-AB9E-05D32,7D66222
2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopp,ed state).'
,[ThaliCore] BrowserManager.disconnect peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62344
[ThaliCore] Session.disconnect() p,eer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1F9CF035-7C79-49E4-8780-3D74C1CE7552
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8B4002AF-5693-4A9C-8936-EBDF28F012EE
[ThaliCore] Browser.startListening
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-26 15:26:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"426C00EC-1CE1-4DA1-851F-9CDEFAD204,3E","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 426C00EC-1CE1-4DA1-851F-9CDEFAD2043E, (syncValue: B8WxidTw5mPUbls7FyynsscqF2nZJY6s)'
,2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42,6C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:426C00EC-1CE1-4DA1,-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "46249FE6-A2BF-4D4C-9A,03-DFBFF2838CA1", generation: 0)
,2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CEA74DD1-9E19-42C5-827A-AEC245524BBC","generation":0}'
,2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1","generation":0}'
,2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
2017-07-26 15:26:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ACCCCDA0-56FC-4073-BDCB-B144AD313CF5","generation":0}'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,6C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,26C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,6C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,26C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,6C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,26C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
,[ThaliCore] Session.deinit peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,6C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:426C00EC,-1CE1-4DA1-851F-9CDEFAD2043E error: max retries exceeded
2017-07-26 15:27:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"B8WxidTw5mPUbls7FyynsscqF2nZJY6s","error":"Connection could not be established","portNumber":null}'
2017-0,7-26 15:27:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'B8WxidTw5mPUbls7FyynsscqF2nZJY6s', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-26 15:27:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-26 15:27:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1 (syncValue: kpPaeEo,zeZmHwpnWOhGZdm7tZxrob1Z6)'
2017-07-26 15:27:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:46249FE6-A2BF,-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:27:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62363
2017-07-26 15:27:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kpPaeEozeZmHwpnWOhGZdm7tZxrob1Z6",,"error":null,"portNumber":62363}'
2017-07-26 15:27:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kpPaeEozeZmHwpnWOhGZdm7tZxrob1Z6', error: 'null', listeningPort: '62363''
Connecting to the localhost:62363
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [4, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:62363
,2017-07-26 15:27:04 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-26 15:27:04 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [4]
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
,2017-07-26 15:27:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:27:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:1F9CF035-7C79-49E4-8780-3D74C1CE7552
2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15,:,27:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62363
[ThaliCore] Session.disconnect() p,eer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BF9402D3-086D-4F63-9EE4-355E475E1C1F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BF9402D3-086D-4F63-9EE4-355E475E1C1F
,2017-07-26 15:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:27:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2D69FF67-E20B-4C6E-B51F-63271D0691E5
,[ThaliCore] Browser.startListening
,2017-07-26 15:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:27:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"46249FE6-A2BF-4D4C-9A03-DFBFF2838C,A1","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1 (syncValue: uzUd8AAkKSHoPMPQE03T81rDSIBkgSPR)'
,2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[T,haliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ACCCCDA0-56FC-4073-BDCB-B144AD313CF5","generation":0}'
,2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
2017-07-26 15:27:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8FBD35BB-A103-436A-9CB9-3B7507AA53AB","generation":0}'
2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: 0)
,2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"83EC259A-93F4-41CE-9EE5-01F8A89A9E61","generation":0}'
,2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF9402D3-086D-4F63-9EE4-355E475E1C1F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF9402D3-086D-4F63-9EE4-355E475E1C1F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:46,249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,6249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:46,249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,6249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:46,249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,6249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:46,249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:46249FE6,-A2BF-4D4C-9A03-DFBFF2838CA1 error: max retries exceeded
2017-07-26 15:27:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uzUd8AAkKSHoPMPQE03T81rDSIBkgSPR","error":"Connection could not be established","portNumber":null}'
2017-0,7-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uzUd8AAkKSHoPMPQE03T81rDSIBkgSPR', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-26 15:27:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8FBD35BB-A103-436A-9CB9-3B7507AA53AB (syncValue: Cva2J9M,NHeYCkiwrdcdetTuiS9oPox3b)'
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8FBD35BB-A103,-436A-9CB9-3B7507AA53AB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62379
,2017-07-26 15:27:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Cva2J9MNHeYCkiwrdcdetTuiS9oPox3b","error":null,"portNumber":62379}'
,2017-07-26 15:27:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Cva2J9MNHeYCkiwrdcdetTuiS9oPox3b', error: 'null', listeningPort: '62379''
,Connecting to the localhost:62379
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
,Connected to the localhost:62379
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [4, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-26 15:27:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 ,15:27:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BF9402D3-086D-4F63-9EE4-3,55E475E1C1F
2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62379
[ThaliCore] Session.disconnect() p,eer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9455D14B-DBA2-4859-9D0F-C21F8AF5CE80", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9455D14B-DBA2-4859-9D0F-C21F8AF5CE80
2017-07-26 1,5:27:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:27:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BCB9EE0A-C80E-4A3F-9884-3E1A867414F6
[ThaliCore] Browser.startListening
2017-07,-26 15:27:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:27:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not m,atch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate, (was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:6EF2B7C6-F5B1-4B26-8675-94DED121B6CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9455D14B-DBA2-4859-9D0F-C21F8AF5CE80
2017-07-26 15:27:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0
2017-07-26 15:27:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F5E673DA-CC95-4DE6-A149-C,189F65599D6", generation: 0)
2017-07-26 15:27:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListe,ning()
2017-07-26 15:27:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:33 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:33 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-26 15:27:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C37878BF-8694-47A0-A8EB-2275F3E2E584
,[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4C7C40DD-0C3D-4460-B197-116DAEC6E216", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4C7C40DD-0C3D-4460-B197-116DAEC6E216
ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopA,dvertising() peerID:4C7C40DD-0C3D-4460-B197-116DAEC6E216
ok 113 discoveryActive should be false
,ok 114 advertisingActive should be true
ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:34 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-26 15:27:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-26 15:27:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-26 15:27:35 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-26 15:27:35 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-26 15:27:35 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-26 15:27:36 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:44b99271-2c0c-456d-b18f-30d233764f5d error: startListeningNotActive
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QcARX8iyCLPADZw1flZOf43QzPdRr3T4","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 129 Should only get called after multiConnect returned
,ok 130 SyncValue matches
,ok 131 Got right error
,ok 132 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5D90475D-A9C3-4A2F-94D5-2A2D0DFA278C
[ThaliCore] Browser.startListening
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-26 15:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 No error on star,ting
ok 134 Got null as expected
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ogdAbeZrM4lbjzMYsyesiQ9lwPG4EUXP","error":"Illegal peerID","portNumber":null}'
ok 135 Should only get called after multiConnect returned
ok 136 SyncValue matches
ok 137 Got right error
ok 138 listeningPort is null
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0)
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F5E673DA-CC95-4DE6-A149-C189F65599D6","generation":0}]'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F5E673DA-CC95-4DE6-A149-C189F65599D6","generation":0}'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-26 15:27:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:90E6B613-24CF-41F6-9D72-77792FAA0614
,[ThaliCore] Browser.startListening
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-26 15:27:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 139 No error on starting
,ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:38 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:38 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:87109005-a081-47ab-b284-5245e6c2d222
,ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:39 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:27:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:58A2E7BB-EEE5-4E37-AD4D-27D548A4E988
,[ThaliCore] Browser.startListening
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-26 15:27:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0)
,ok 144 Can call startListeningForAdvertisements without error
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F5E673DA-CC95-4DE6-A149-C189F65599D6","generation":0}'
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F5E673DA-CC95-4DE6-A149-C189F65599D6 (syncValue: W3kj04Hd9ypcEIfFDaN0AnsH8yqfMFxX)'
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
,2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C4BE094-B690-45C8-8D11-640C8096028F","generation":0}'
,2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85616D03-A4E2-454E-A6D7-D1E511D69A3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85616D03-A4E2-454E-A6D7-D1E511D69A3B", generation: 0)
2017-07-26 15:27:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"85616D03-A4E2-454E-A6D7-D1E511D69A3B","generation":0}'
2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:40 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F5,E673DA-CC95-4DE6-A149-C189F65599D6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F5,E673DA-CC95-4DE6-A149-C189F65599D6:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-26 15:27:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"W3kj04Hd9ypcEIfFDaN0AnsH8yqfMFxX","error":"Peer is unavailable",,"portNumber":null}'
2017-07-26 15:27:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'W3kj04Hd9ypcEIfFDaN0AnsH8yqfMFxX', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-26 15:27:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-26 15:27:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6C4BE094-B690-45C8-8D11-640C8096028F (syncValue: j1c7cjnooGFxtoM3LWZ2Xb0,oNOxVfoPz)'
2017-07-26 15:27:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6C4BE094-B690-45C8-8D11-640C8,096028F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:27:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:626BD7C4-443D-4AE5-8DE1-709B880C531F
[ThaliCore] Advertiser: session connected Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:626BD7C4-443D-4AE5-8DE1-709B880C531F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:626BD7C4-443D-4AE5-8DE1-709B880C531F
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62392
,2017-07-26 15:27:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"j1c7cjnooGFxtoM3LWZ2Xb0oNOxVfoPz","error":null,"portNumber":62392}'
,2017-07-26 15:27:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'j1c7cjnooGFxtoM3LWZ2Xb0oNOxVfoPz', error: 'null', listeningPort: '62392''
,[ThaliCore] Session.session(_:peer:didChange:) peer:626BD7C4-443D-4AE5-8DE1-709B880C531F state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:626BD7C4-443D-4AE5-8DE1-709B880C531F
[ThaliCore] Session.startOutputStream(with:) peer:626BD7C4-443D-4AE5-8DE1-709B880C531F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [4, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,ok 145 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0) found active relay
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
2017-07-26 15:27:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zB5IWLlGri1kYlEW1Jxp6CbwJBSMBqzH","error":null,"portNumber":62392}'
,ok 146 No error
,ok 147 Ports equal
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0) found active relay
,2017-07-26 15:27:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1r85sES9RUg5XtfsHtcKqJj8klugoVe5","error":null,"portNumber":62392}'
,ok 149 No error
,ok 150 Ports equal
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [4, 8, 9, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,# teardown
,2017-07-26 15:27:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:27:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-26 15:27:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:9
[ThaliCore] VirtualSocket.closeSt,reams() vsID:9
,[ThaliCore] BrowserManager.disconnect peer:6C4BE094-B690-45C8-8D11-640C8096028F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62392
[ThaliCore] VirtualSocket.closeStr,eams() vsID:10
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [4, 8, 10]
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:10 [4, 8]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:626BD7C4-443D-4AE5-8DE1-709B880C531F state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:626BD7C4-443D-4AE5-8DE1-709B880C531F
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"j1c7cjnooGFxtoM3LWZ2Xb0oNOxVfoPz","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:626BD7C4-443D-4AE5-8DE1-709B880C531F
,[ThaliCore] Session.deinit peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] BrowserRelay.deinit
,# initial peer discovery
,2017-07-26 15:27:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-26 15:27:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-26 15:27:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-26 15:27:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-26 15:27:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-26 15:27:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:52 - DEBUG createNativeListener: 'listening 62396'
ok 151 Should throw
,# teardown
,2017-07-26 15:27:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:52 - DEBUG createNativeListener: 'listening 62398'
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'listening 62401'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'listening 62405'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'listening 62410'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
,ok 163 incoming remains open
,# teardown
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - close'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'listening 62414'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 164 we should not have gotten an error
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'listening 62418'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'listening 62422'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 170 we should not have gotten an error
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'listening 62426'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - ,0 - 1 - created'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client con,nection to node - 0 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-26 15:27:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-26 15:27:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:57 - DEBUG createNativeListener: 'listening 62478'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 181 we should not have gotten an error
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 183 server should be fine
,ok 184 server should be open
,ok 185 incoming has been removed
,ok 186 The mux object should be closed
,ok 187 The mux stream should be closed
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-26 15:27:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:57 - DEBUG createNativeListener: 'listening 62482'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:58 - DEBUG createNativeListener: 'listening 62485'
ok 198 port must be in range
,# teardown
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:58 - DEBUG createNativeListener: 'listening 62486'
ok 199 second start should return same port
,# teardown
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'listening 62488'
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should be connected
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 now we are disconnected
,2017-07-26 15:27:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-26 15:27:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-26 15:27:59 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 202 Passed bogus id
,2017-07-26 15:27:59 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 203 Passed good id but bogus port
,2017-07-26 15:27:59 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 204 Passed right context
,ok 205 Right server
,ok 206 No error should be set
,ok 207 Retry should be false
,ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 62490
,ok 209 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:85E620C7-FC44-4A79-A50E-96D2E16AC7DB
,2017-07-26 15:28:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:28:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:28:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browse,r.init(serviceType:foundPeer:lostPeer:) peer:CD2D2900-859F-4060-B1A1-93BBF790160E
[ThaliCore] Browser.startListening
2017-07-26 15:28:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive",:true}'
,2017-07-26 15:28:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-26 15:28:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85616D03-A4E2-454E-A6D7-D1E511D69A3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85616D03-A4E2-454E-A6D7-D1E511D69A3B", generation: 0)
2017-07-26 15:28:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C4BE094-B690-45C8-8D11-640C8096028F","generation":0}'
,2017-07-26 15:28:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6C4BE094-B690-45C8-8D11-640C8096028F (syncValue: FoViL5YpIQZun7NYpg5G7SZk28qd4mv1)'
2017-07-26 15:28:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:28:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"85616D03-A4E2-454E-A6D7-D1E511D69A3B","generation":0}'
,2017-07-26 15:28:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:28:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E937297E-E1AB-49DC-8BCB-38DF5390140B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:34B62C2A-F0EA-47B5-919A-775C72B2336C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0)
2017-07-26 15:28:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E937297E-E1AB-49DC-8BCB-38DF5390140B","generation":0}'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"34B62C2A-F0EA-47B5-919A-775C72B2336C","generation":0}'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85E620C7-FC44-4A79-A50E-96D2E16AC7DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,C4BE094-B690-45C8-8D11-640C8096028F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:85616D03-A4E2-454E-A6D7-D1E511D69A3B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "85616D03-A4E2-454E-A6D7-D1E511D69A3B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,C4BE094-B690-45C8-8D11-640C8096028F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,C4BE094-B690-45C8-8D11-640C8096028F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-26 15:28:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FoViL5YpIQZun7NYpg5G7SZk28qd4mv1","error":"Peer is unavailable",,"portNumber":null}'
2017-07-26 15:28:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FoViL5YpIQZun7NYpg5G7SZk28qd4mv1', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-26 15:28:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-26 15:28:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E937297E-E1AB-49DC-8BCB-38DF5390140B (syncValue: yQvDZkfYAwTtSpfHq87w9mr,UhWNnCIQq)'
2017-07-26 15:28:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E937297E-E1AB-49DC-8BCB-38DF5,390140B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:28:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:918FA0EB-D427-4759-8534-4F28BA1762FA
[ThaliCore] Advertiser: session connected Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:918FA0EB-D427-4759-8534-4F28BA1762FA state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E937297E-E1AB-49DC-8BCB-38DF5390140B:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ADD585A6-B453-4207-A436-7E31657DF966
[ThaliCore] Advertiser: session connected Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ADD585A6-B453-4207-A436-7E31657DF966 state: notConnected -> connecting
,2017-07-26 15:28:10 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:918FA0EB-D427-4759-8534-4F28BA1762FA
,[ThaliCore] Session.session(_:peer:didChange:) peer:918FA0EB-D427-4759-8534-4F28BA1762FA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E937297E-E1AB-49DC-8BCB-38DF5390140B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E937297E-E1AB-49DC-8BCB-38DF5390140B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62502
,2017-07-26 15:28:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yQvDZkfYAwTtSpfHq87w9mrUhWNnCIQq","error":null,"portNumber":62502}'
,2017-07-26 15:28:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yQvDZkfYAwTtSpfHq87w9mrUhWNnCIQq', error: 'null', listeningPort: '62502''
,ok 212 should be equal
,2017-07-26 15:28:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 34B62C2A-F0EA-47B5-919A-775C72B2336C (syncValue: D4xBIWcMPLveiRBd1Vuh9YUUhOWvDLf2)'
,2017-07-26 15:28:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:34B62C2A-F0EA-47B5-919A-775C72B2336C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:34B62C2A-F0EA-47B5-919A-775C72B2336C:0 state: notConnected -> connecting
,2017-07-26 15:28:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4,EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ADD585A6-B453-4207-A436-7E31657DF966
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADD585A6-B453-4207-A436-7E31657DF966 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:34B62C2A-F0EA-47B5-919A-775C72B2336C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:34B62C2A-F0EA-47B5-919A-775C72B2336C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62507
,2017-07-26 15:28:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"D4xBIWcMPLveiRBd1Vuh9YUUhOWvDLf2","error":null,"portNumber":62507}'
2017-07-26 15:28:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'D,4xBIWcMPLveiRBd1Vuh9YUUhOWvDLf2', error: 'null', listeningPort: '62507''
,ok 213 should be equal
,# teardown
,2017-07-26 15:28:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4,EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-26 15:29:15 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Single coordinated request ios native, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B9,3DC4/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/tim,ers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-07-26 15:29:15 - ERROR Coordi,natedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-26 15:29:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4,EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4,EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4,EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4,EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:35 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:350:16
$9@timers.,js:120:1
''
,2017-07-26 15:31:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4,EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4,EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4,EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4,EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EF,A-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:43 - ERROR CoordinatedClient: 'reconnect_failed error: 'undefined', description: '%s', stack: '%s''
2017-07-26 15:44:43 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-26 15:44:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4,EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7E06FB6B-0318-4EFA-A22A-E24F60B93DC4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:43 - DEBUG CoordinatedThaliTape: 'all tests succeed'
,2017-07-26 15:44:43 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
