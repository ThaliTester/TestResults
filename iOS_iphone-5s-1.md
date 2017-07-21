#### Test 113351851f8c1845_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851f8c1845/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/10F32119-5FC7-4A7A-B43C-037FAAFD1C29/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/10F32119-5FC7-4A7A-B43C-037FAAFD1C29/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851f8c1845/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851f8c1845/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60742"
,(lldb)     command script import "/tmp/10F32119-5FC7-4A7A-B43C-037FAAFD1C29/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,2017-07-21 10:53:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:53:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:53:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:53:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:53:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:53:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4C7583DC-9ACD-4DD5-9C2A-02E8F4E59323", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4C7583DC-9ACD-4DD5-9C2A-02E8F4E59323
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FE3288B8-E2CF-4BB2-B270-CA37FD66A9AC
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7AA23377-,9AB3-4CD1-9D6C-CF31041DED57
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CCCFB5EA-0E70-426B-9BF0-F42D2EA13B65", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:CCCFB5EA-0E70-426B-9BF0-F42D2EA13B65
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CCCFB5EA-0E70-426B-9BF0-F42D2EA13B65:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CCCFB5EA-0E70-426B-9BF0-F42D2EA13B65", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-21 10:53:44 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Nu,mber of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.437393069267273
,2017-07-21 10:53:44 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-07-21 10:53:44 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CCCFB5EA-0E70-426B-9BF0-F42D2EA13B65:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CCCFB5EA-0E70-426B-9BF0-F42D2EA13B65", generation: 0)
,2017-07-21 10:53:48 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 10:53:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 10:53:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 10:53:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 10:53:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 10:53:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 10:53:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 10:53:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 10:53:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 10:53:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 10:53:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 10:53:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 10:53:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 10:53:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 10:53:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 10:53:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 10:53:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 10:53:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 10:53:52 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 10:53:52 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 10:53:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:53:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:53:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:53:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:53:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:54:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:54:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:54:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:33 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-21 10:54:33 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 10:54:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-21 10:54:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 10:54:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-21 10:54:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-21 10:54:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-21 10:54:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-21 10:54:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-21 10:54:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
ok 5 should be equal
,ok 6 should be equal
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
ok 25 thirdPromise - in resolve
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
,2017-07-21 10:54:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-21 10:54:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-21 10:54:58 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 53 participant data matches
,ok 54 test participant has uuid
,ok 55 participant data matches
,ok 56 own UUID is found from the participants list
,# teardown
,# setup
,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-21 10:55:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 10:55:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AEA2C676-5B3E-4CAE-B53E-4BA920F52CBE
[ThaliCore] Browser.startListening
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-21 10:55:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:16 - INFO tha,l,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:16 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:87B70B00-0705-4EC7-9691-935DC25AEE77
[ThaliCore] Browser.startListening
,2017-07-21 10:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:55:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:55:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 10:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:55:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:55:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:55:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:55:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:55:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:25 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:25 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "66828CDC-A7F3-4A48-9B0A-7BF690200A6D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:66828CDC-A7F3-4A48-9B0A-7BF690200A6D
2017-07-21 1,0:55:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:66828CDC-A7F3-4A48-9B0A-7BF690200A6D
2017-07-21 10:55:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D2A5CD3E-CDED-4BB6-81F4-3C4D699F05B6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D2A5CD3E-CDED-4BB6-81F4-3C4D699F05B6
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D2A5CD3E-CDED-4BB6-81F4-3C4D699F05B6", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:D2A5CD3E-CDED-4BB6-81F4-3C4D699F05B6
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D2A5CD3E-CDED-4BB6-81F4-3C4D699F05B6
[ThaliCore] Advertiser.stopAdvertising() peerID:D2A5CD3E-CDED-4BB6-81F4-3C4D699F05B6,
2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e).'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive",:false}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E7E89EFF-C927-4E61-88A8-AA1DF588DD01", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E7E89EFF-C927-4E61-88A8-AA1DF588DD01
2017-07-21 1,0:55:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1A94B3B8-B509-4775-93EF-90C34419BBD6
[Thali,C,ore] Browser.startListening
2017-07-21 10:55:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:55:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 10:55:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7E89EFF-C927-4E61-88A8-AA1DF588DD01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7E89EFF-C927-4E61-88A8-AA1DF588DD01", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C698F9B2-FB30-44D1-8818-CDAB79F25800:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C698F9B2-FB30-44D1-8818-CDAB79F25800", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFC46F12-BB3B-4698-909C-4C2A69860CF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFC46F12-BB3B-4698-909C-4C2A69860CF7", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:55:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E7E89EFF-C927-4E61-88A8-AA1DF588DD01
2017-07-21 10:55:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:55:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,anged registered to native'
,2017-07-21 10:55:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB
2017-07-21 1,0:55:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EB1B9D40-B842-46BA-8EE0-88D3C99582B0
[ThaliCore] Browser.startListe,ning
2017-07-21 10:55:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:55:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisi,ngStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0)
2017-07-21 10:55:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9322C209-D516-4AC3-B9B3-B33D7BDE94FF","generation":0}'
2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9322C209-D516-4AC3-B9B3-B33D7BDE94FF, (syncValue: Fx5021jaqlgCCKyRWJt8wxYnhZPfRdLX)'
,2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5964CC8A-CCBB-402E-9185-5196A4325050","generation":0}'
,2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57958
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Fx5021jaqlgCCKyRWJt8wxYnhZPfRdLX","error":null,"portNumber":57958}'
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Fx5021jaqlgCCKyRWJt8wxYnhZPfRdLX', error: 'null', listeningPort: '57958''
,2017-07-21 10:55:43 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-21 10:55:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57958
,[ThaliCore] Session.disconnect() peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F
2017-07-21 1,0:55:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2DA78DBA-B755-423F-8440-7648D04FC359
[ThaliCore] Browser.startListe,ning
2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:55:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 10:55:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"84A788E4-46FC-43D7-85F3-930F387C1ABA","generation":0}'
2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 84A788E,4-46FC-43D7-85F3-930F387C1ABA (syncValue: p6OwK9ywp6M4nkGhJyyj9bnJVCnrBeb5)'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5964CC8A-CCBB-402E-9185-5196A4325050","generation":0}'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C6A107A9-3C3D-474E-BE7A-580D8B57BEF0","generation":0}'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57962
2017-07-21 10:55:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"p6OwK9ywp6M4nkGhJyyj9bnJVCnrBeb5",,"error":null,"portNumber":57962}'
,2017-07-21 10:55:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'p6OwK9ywp6M4nkGhJyyj9bnJVCnrBeb5', error: 'null', listeningPort: '57962''
,Connecting to the localhost:57962
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
,Connected to the localhost:57962
,2017-07-21 10:55:48 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-21 10:55:48 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E054CB27-C059-42DF-A078-AA7174A3B4AD
[ThaliCore] Advertiser: session connected Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E054CB27-C059-42DF-A078-AA7174A3B4AD state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E054CB27-C059-42DF-A078-AA7174A3B4AD
,[ThaliCore] Session.session(_:peer:didChange:) peer:E054CB27-C059-42DF-A078-AA7174A3B4AD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E054CB27-C059-42DF-A078-AA7174A3B4AD
[ThaliCore] Session.startOutputStream(with:) peer:E054CB27-C059-42DF-A078-AA7174A3B4AD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 10:55:59 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 10:55:59 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 10:55:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-21 10:55:59 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 10:55:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:55:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E054CB27-C059-42DF-A078-AA7174A3B4AD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E054CB27-C059-42DF-A078-AA7174A3B4AD
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:84A788E4-46FC-43D7-85F3-930F387C1ABA
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57962
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"p6OwK9ywp6M4nkGhJyyj9bnJVCnrBeb5","error":"Session disconnected","portNumber":null}'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"84A788E4-46FC-43D7-85F3-930F387C1ABA","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"84A788E4-46FC-43D7-85F3-930F387C1ABA","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C6E0D61B-5C67-46BA-BD6E-1062AC583801
2017-07-21 1,0:56:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:56:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7FD124B6-9004-4F01-855D-07531362FDF7
[Thali,Core] Browser.startListening
2017-07-21 10:56:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:56:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:00 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:E054CB27-C059-42DF-A078-AA7174A3B4AD
[ThaliCore] Session.deinit peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
2017-07-21 10:56:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"84A788E4-46FC-43D7-85F3-930F387C1ABA","generation":0}'
2017-07-21 10:56:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 84A788E4-46FC-43D7-85F3-930F387C1ABA, (syncValue: 5KOBYeyzN0yxZrQRmxRpleKqFp4PzhjZ)'
2017-07-21 10:56:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387,C1ABA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:56:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"C6A107A9-3C3D-474E-BE7A-580D8B57BEF0","generation":0}'
,2017-07-21 10:56:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
2017-07-21 10:56:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"62EDF300-F62B-48E1-984D-71A5F52E35C1","generation":0}'
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:01 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86","generation":0}'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,4A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,4A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,4A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:84A788E4,-46FC-43D7-85F3-930F387C1ABA error: max retries exceeded
2017-07-21 10:56:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5KOBYeyzN0yxZrQRmxRpleKqFp4PzhjZ","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 10:56:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5KOBYeyzN0yxZrQRmxRpleKqFp4PzhjZ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 10:56:11 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"84A788E4-46FC-43D7-85F3-930F387C1ABA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:56:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 10:56:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"84A788E4-46FC-43D7-85F3-930F387C1ABA","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 10:56:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 10:56:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 62EDF300-F62B-48E1-984D-71A5F52E35C1 (syncValue: noTsKc5,2ns1fCkk9bXWBzqmZiWCDidpK)'
2017-07-21 10:56:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:62EDF300-F62B,-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:56:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57972
2017-07-21 10:56:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"noTsKc52ns1fCkk9bXWBzqmZiWCDidpK",,"error":null,"portNumber":57972}'
2017-07-21 10:56:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'noTsKc52ns1fCkk9bXWBzqmZiWCDidpK', error: 'null', listeningPort: '57972''
,Connecting to the localhost:57972
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
,Connecting to the localhost:57972
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
,Connecting to the localhost:57972
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
,Connected to the localhost:57972
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:57972
,Connected to the localhost:57972
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-21 10:56:17 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5]
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:4 [5]
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 96 got the same data back
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
,2017-07-21 10:56:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] VirtualSocket.deinit vsID:5 []
,2017-07-21 10:56:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C6E0D61B-5C67-46BA-BD6E-1062AC583801
2017-07-2,1 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:62EDF300-F62B-48E1-984D-71A5F52E35C1
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57972
[ThaliCore] Session.disconnect() p,eer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"noTsKc52ns1fCkk9bXWBzqmZiWCDidpK","error":"Session disconnected","portNumber":null}'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"62EDF300-F62B-48E1-984D-71A5F52E35C1","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"62EDF300-F62B-48E1-984D-71A5F52E35C1","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:56:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:45BB0A59-DDD2-4E70-A7A6-C155709B070B
[ThaliCore] Browser.startListening
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:56:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3FDC5DDB-7B8C-46BB,-9035-E7915D9CA128:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86 (syncValue: xh9fpQZEIkFhsuOls3GaRz6yKCsPH03O)'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
2017-07-21 10:56:20, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C","generation":0}'
2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:20 - DEBUG, thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7,D945274", generation: 0)
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9BD2EEC5-BC28-4301-8B46-0C2C7D945274","generation":0}'
2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F0,C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F0,C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DD1CD578-EC72-404F-BAE8-994A42F04A88
[ThaliCore] Advertiser: session connected Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DD1CD578-EC72-404F-BAE8-994A42F04A88 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F0,C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2802489A-F04F-493C-B788-CCEF365DA525
[ThaliCore] Advertiser: session connected Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2802489A-F04F-493C-B788-CCEF365DA525 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F0,C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:F0C64DD8,-128D-45A0-B3D4-36BE8B3AAC86 error: max retries exceeded
2017-07-21 10:56:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xh9fpQZEIkFhsuOls3GaRz6yKCsPH03O","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 10:56:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xh9fpQZEIkFhsuOls3GaRz6yKCsPH03O', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 10:56:31 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:56:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:56:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:31 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 10:56:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C (syncValue: D4LPqabO110K7lGXDJXXCH8mdN7rG2Iy)'
,2017-07-21 10:56:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:56:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DD1CD578-EC72-404F-BAE8-994A42F04A88
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD1CD578-EC72-404F-BAE8-994A42F04A88 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD1CD578-EC72-404F-BAE8-994A42F04A88
[ThaliCore] Session.startOutputStream(with:) peer:DD1CD578-EC72-404F-BAE8-994A42F04A88
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0 state: notConnected -> connecting
,2017-07-21 10:56:32 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 10:56:32 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 10:56:32 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-21 10:56:32 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 10:56:32 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 []
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2802489A-F04F-493C-B788-CCEF365DA525
,[ThaliCore] Session.session(_:peer:didChange:) peer:2802489A-F04F-493C-B788-CCEF365DA525 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2802489A-F04F-493C-B788-CCEF365DA525
[ThaliCore] Session.startOutputStream(with:) peer:2802489A-F04F-493C-B788-CCEF365DA525
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57992
,2017-07-21 10:56:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"D4LPqabO110K7lGXDJXXCH8mdN7rG2Iy","error":null,"portNumber":57992}'
,2017-07-21 10:56:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'D4LPqabO110K7lGXDJXXCH8mdN7rG2Iy', error: 'null', listeningPort: '57992''
,Connecting to the localhost:57992
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
,Server received psk id: psk-id
,2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] VirtualSocket.closeSt,reams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 []
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:57992
2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 []
,# teardown
,2017-07-21 10:56:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:56:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57992
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2802489A-F04F-493C-B788-CCEF365DA525 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2802489A-F04F-493C-B788-CCEF365DA525
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD1CD578-EC72-404F-BAE8-994A42F04A88 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:56:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"D4LPqabO110K7lGXDJXXCH8mdN7rG2Iy","error":"Session disconnected","portNumber":null}'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# Can shift large amounts of data
,[ThaliCore] Session.deinit peer:2802489A-F04F-493C-B788-CCEF365DA525
[ThaliCore] Session.deinit peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F287E759-9DEE-41EC-A28C-0C2B4889AF65", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F287E759-9DEE-41EC-A28C-0C2B4889AF65
,2017-07-21 10:56:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:56:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:56:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B04A5574-A5F0-4CCE-9CD8-297EFD329A4A
,[ThaliCore] Browser.startListening
,2017-07-21 10:56:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:56:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:56:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
2017-07-21 10:56:37 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9BD2EEC5-BC28-4301-8B46-0C2C7D945274","generation":0}'
2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9BD2EEC5-BC28-4301-8B46-0C2C7D945274, (syncValue: TDkNsOXUZyOsoI3fDE9xwc4DJfnBtupz)'
2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D9,45274", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:839E6042-1808-4159-8923-FD521909AFE8:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
2017-07-21 10:56:37, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"839E6042-1808-4159-8923-FD521909AFE8","generation":0}'
2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:37 - DEBUG, thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
,2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}'
,2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F287E759-9DEE-41EC-A28C-0C2B4889AF65:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F287E759-9DEE-41EC-A28C-0C2B4889AF65", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9B,D2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9B,D2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:56:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TDkNsOXUZyOsoI3fDE9xwc4DJfnBtupz","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:56:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TDkNsOXUZyOsoI3fDE9xwc4DJfnBtupz', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:56:42 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"9BD2EEC5-BC28-4301-8B46-0C2C7D945274","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:56:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 10:56:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9BD2EEC5-BC28-4301-8B46-0C2C7D945274","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-21 10:56:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:56:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 839E6042-1808-4159-8923-FD521909AFE8 (syncValue: gapaKy3ss6LSXB1VdrvF3gt,xxjqt3f8a)'
2017-07-21 10:56:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:839E6042-1808-4159-8923-FD521,909AFE8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:56:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:839E6042-1808-4159-8923-FD521909AFE8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:839E6042-1808-4159-8923-FD521909AFE8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:839E6042-1808-4159-8923-FD521909AFE8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58004
2017-07-21 10:56:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gapaKy3ss6LSXB1VdrvF3gtxxjqt3f8a",,"error":null,"portNumber":58004}'
2017-07-21 10:56:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gapaKy3ss6LSXB1VdrvF3gtxxjqt3f8a', error: 'null', listeningPort: '58004''
,Connecting to the localhost:58004
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:839E6042-1808-4159-8923-FD521909AFE8:0
,Connected to the localhost:58004
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:839E6042-1808-4159-8923-FD521909AFE8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:56:45 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 10:56:45 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:9
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-21 10:56:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,10:56:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 10:56:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F287E759-9DEE-41EC-A28C-0,C2B4889AF65
2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:56:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:839E6042-1808-4159-8923-FD521909AFE8
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58004
[ThaliCore] Session.disconnect() p,eer:839E6042-1808-4159-8923-FD521909AFE8:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:839E6042-1808-4159-8923-FD521909AFE8:0
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:56:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:809FFCEB-4DAB-42EF-B695-A3777151FE07
[ThaliCore] Browser.startListening
2017-07-21 10:56:58 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:56:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 10:56:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:,errorHandler:) Peer(uuid: "06887905-6ACD-4B62-BBB9-4BB2FDAC62C3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:06887905-6ACD-4B62-BBB9-4BB2FDAC62C3
2017-07-21 10:56:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpda,teNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:56:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"ne,t,workType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:56:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:839E6042-1808-4159-8923-FD521909AFE8:0
2017-07-21 10:56:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
2017-07-21 10:56:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}'
2017-07-21 10:56:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
2017-07-21 10:56:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"839E6042-1808-4159-8923-FD521909AFE8","generation":0}]'
,2017-07-21 10:56:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"839E6042-1808-4159-8923-FD521909AFE8","generation":0}'
,2017-07-21 10:56:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06887905-6ACD-4B62-BBB9-4BB2FDAC62C3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06887905-6ACD-4B62-BBB9-4BB2FDAC62C3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49486435-1B49-404F-8A95-D65FB54627D3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49486435-1B49-404F-8A95-D65FB54627D3", generation: 0)
,2017-07-21 10:56:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"49486435-1B49-404F-8A95-D65FB54627D3","generation":0}]'
,2017-07-21 10:56:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"49486435-1B49-404F-8A95-D65FB54627D3","generation":0}'
,2017-07-21 10:56:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0D7C3221-280B-4FF5-8FC8-0F4B9059DAA1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0D7C3221-280B-4FF5-8FC8-0F4B9059DAA1", generation: 0)
2017-07-21 10:57:01 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0D7C3221-280B-4FF5-8FC8-0F4B9059DAA1","generation":0}]'
2017-07-21 10:57:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0D7C3221-280B-4FF5-8FC8-0F4B9059DAA1","generation":0}'
2017-07-21 10:57:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,10:57:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 10:57:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:06887905-6ACD-4B62-BBB9-4,BB2FDAC62C3
2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-21 10:57:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B15D7FEA-3179-40B5-952A-1946E6E7EC54
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DD7EF68D-9836-475F-A8BF-B494D87559E4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DD7EF68D-9836-475F-A8BF-B494D87559E4
ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DD7EF68D-9836-475F-A8BF-B494D87559E4
,ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-21 10:57:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 10:57:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 10:57:06 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 10:57:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 10:57:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 10:57:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 10:57:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3ef0b6ce-3c0c-4f76-9eae-9efb800bc23b error: startListeningNotActive
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"gLvassQ24U7zXSpgRJ7udhRoZ6oZf2X8","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3ef0b6ce-3c0c-4f76-9eae-9efb800bc23b","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3ef0b6ce-3c0c-4f76-9eae-9efb800bc23b","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:465F15C0-6F97-4342-9D21-744900F547F7
[ThaliCore] Browser.startListening
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:57:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z1ZNwctCioO5q3xgHaa8aECxsguNG62G","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
,ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}]'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 10:57:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F22DEFC2-2031-47B8-A120-C1BCF853F5BE
[ThaliCore] Browser.startListening
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:57:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on star,ting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:2fe24999-a004-4651-b33d-6ab96734c89b
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:18A68881-1F66-4E2F-A9A0-409648231FCA
2017-07-21 1,0:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4AA06938-FA20-4E7B-AA69-D843B64A7770
[ThaliCore] Browser.startListening
2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B (syncValue: oAJeRZzkc6Cwi0OlEdM1IdrQxVbs3Vv3)'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0
2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0)
,2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA","generation":0}'
,2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C4F4C6EC-1245-479D-9812-A32327ECFD8A
[ThaliCore] Session.session(_:peer:didChange:) peer:C4F4C6EC-1245-479D-9812-A32327ECFD8A state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0F,DE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C4F4C6EC-1245-479D-9812-A32327ECFD8A
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4F4C6EC-1245-479D-9812-A32327ECFD8A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4F4C6EC-1245-479D-9812-A32327ECFD8A
[ThaliCore] Session.startOutputStream(with:) peer:C4F4C6EC-1245-479D-9812-A32327ECFD8A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0F,DE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0F,DE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0F,DE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:0FDE9EDA,-3925-4EEE-8C07-B82DDC023D3B error: max retries exceeded
2017-07-21 10:57:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oAJeRZzkc6Cwi0OlEdM1IdrQxVbs3Vv3","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 10:57:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oAJeRZzkc6Cwi0OlEdM1IdrQxVbs3Vv3', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 10:57:21 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:57:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 10:57:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 10:57:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:57:21 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 10:57:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9 (syncValue: GMDIhLyDAWqaxmffJfgPWV91UBr3aF7R)'
,2017-07-21 10:57:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 10:57:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58022
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GMDIhLyDAWqaxmffJfgPWV91UBr3aF7R","error":null,"portNumber":58022}'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GMDIhLyDAWqaxmffJfgPWV91UBr3aF7R', error: 'null', listeningPort: '58022''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
,ok 143 Got null as expected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0) found a,ctive relay
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [9, 10, 11]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DlyOfMh0fP1DUweYksSSN9jBSQttxMJf","error":null,"portNumber":58022}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0) found active relay
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"agvQWJfHcHve8eO9eRXgufFT583n9VLc","error":null,"portNumber":58022}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,2017-07-21 10:57:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeS,treams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [9, 11]
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:57:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:57:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:18A68881-1F66-4E2F-A9A0-409648231FCA
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58022
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:11 [9]
,[ThaliCore] Session.disconnect() peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4F4C6EC-1245-479D-9812-A32327ECFD8A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C4F4C6EC-1245-479D-9812-A32327ECFD8A
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GMDIhLyDAWqaxmffJfgPWV91UBr3aF7R","error":"Session disconnected","portNumber":null}'
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:C4F4C6EC-1245-479D-9812-A32327ECFD8A
,# initial peer discovery
,2017-07-21 10:57:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 10:57:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 10:57:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-21 10:57:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-21 10:57:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 10:57:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 10:57:27 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:27 - DEBUG createNativeListener: 'listening 58025'
,ok 149 Should throw
,# teardown
,2017-07-21 10:57:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:27 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'listening 58027'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'listening 58030'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'listening 58034'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client co,nnection to node - 0 - 0 - closed'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'listening 58039'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'listening 58043'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:30 - DEBUG createNativeListener: 'listening 58047'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'listening 58051'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'listening 58055'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 10:57:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 10:57:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:32 - DEBUG createNativeListener: 'listening 58107'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'listening 58111'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'listening 58114'
ok 196 port must be in range
,# teardown
,2017-07-21 10:57:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:33 - DEBUG createNativeListener: 'listening 58115'
ok 197 second start should return same port
,# teardown
,2017-07-21 10:57:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 10:57:34 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:34 - DEBUG createNativeListener: 'listening 58117'
,2017-07-21 10:57:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
,2017-07-21 10:57:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-21 10:57:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 10:57:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 10:57:34 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-21 10:57:34 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-21 10:57:34 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 58119
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7C3D7BAF-2475-406D-A529-BAFFF20512EB
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:57:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D538D25B-4837-4E0A-920D-A933F5A48F3B
,[ThaliCore] Browser.startListening
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
2017-07-21 10:57:34 - INFO th,aliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}}),'
2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9","generation":0}'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9 (syncValue: vzx8xoICO0rgifaVn6Uw83Zc2A095IxP)'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
,2017-07-21 10:57:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ACEDB61A-DE2E-4167-AED9-3A55C192CFAF","generation":0}'
,2017-07-21 10:57:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
2017-07-21 10:57:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3","generation":0}'
2017-07-21 10:57:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:36 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4F,57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0D133F74-EC2E-4B96-A318-6FC3B07FF232
[ThaliCore] Advertiser: session connected Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0D133F74-EC2E-4B96-A318-6FC3B07FF232 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4F,57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4F,57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:57:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vzx8xoICO0rgifaVn6Uw83Zc2A095IxP","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:57:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vzx8xoICO0rgifaVn6Uw83Zc2A095IxP', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:57:43 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:57:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
,2017-07-21 10:57:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 10:57:43 - DEBUG thaliMobile,NativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:57:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 10:57:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ACEDB61A-DE2E-4167-AED9-3A55C192CFAF (syncValue: YiZhpxIDrsfg0JOZLQ2n5Aa37j8dYX9Y)'
,2017-07-21 10:57:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0D133F74-EC2E-4B96-A318-6FC3B07FF232
,2017-07-21 10:57:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D133F74-EC2E-4B96-A318-6FC3B07FF232 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06D0FB89-E071-47C1-A098-41347350B3A8
[ThaliCore] Advertiser: session connected Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:06D0FB89-E071-47C1-A098-41347350B3A8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58131
,2017-07-21 10:57:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YiZhpxIDrsfg0JOZLQ2n5Aa37j8dYX9Y","error":null,"portNumber":58131}'
,2017-07-21 10:57:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YiZhpxIDrsfg0JOZLQ2n5Aa37j8dYX9Y', error: 'null', listeningPort: '58131''
,ok 210 should be equal
,2017-07-21 10:57:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3 (syncValue: qUt3Xw0pI2KEcn76OfX406SZ1FJMq6oN)'
,2017-07-21 10:57:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:06D0FB89-E071-47C1-A098-41347350B3A8
,[ThaliCore] Session.session(_:peer:didChange:) peer:06D0FB89-E071-47C1-A098-41347350B3A8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58135
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qUt3Xw0pI2KEcn76OfX406SZ1FJMq6oN","error":null,"portNumber":58135}'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qUt3Xw0pI2KEcn76OfX406SZ1FJMq6oN', error: 'null', listeningPort: '58135''
,ok 211 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,10:57:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 10:57:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7C3D7BAF-2475-406D-A529-B,AFFF20512EB
2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58131
[ThaliCore] Session.disconnect() p,eer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58135
,[ThaliCore] Session.disconnect() peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D133F74-EC2E-4B96-A318-6FC3B07FF232 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:06D0FB89-E071-47C1-A098-41347350B3A8
,[ThaliCore] Session.deinit peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 10:57:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai,labilityChanged registered to native'
2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:06D0FB89-E071-47C1-A098-41347350B3A8
[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 58137
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:50 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:57:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-2,1 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:93A0D9D1-6F45-4D45-8431-EC83225FE394
2017-07-21 1,0:57:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:57:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F
[ThaliCore] Browser.startListening
2017-07-21 10:57:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 10:57:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
2017-07-21 10:57:52 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3 (syncValue: tQvsi9LLJYK57Tnm,8Biavn1unKWHJtcT)'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[T,haliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ACEDB61A-DE2E-4167-AED9-3A55C192CFAF","generation":0}'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","generation":0}'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,D6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,D6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,D6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4931A5EF-19CB-4D3A-ACD4-6195FBE307AC
[ThaliCore] Advertiser: session connected Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4931A5EF-19CB-4D3A-ACD4-6195FBE307AC state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:ED6CFA85,-1D6F-4A9C-AF83-CBE3587A10C3 error: max retries exceeded
2017-07-21 10:58:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tQvsi9LLJYK57Tnm8Biavn1unKWHJtcT","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 10:58:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tQvsi9LLJYK57Tnm8Biavn1unKWHJtcT', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 10:58:03 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:58:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:58:03 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 10:58:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5CF26575-49BF-4D5C-BE65-95FBD5115ED6 (syncValue: F1wDh6jycyb9IbBavuiSq7GktuU86T09)'
,2017-07-21 10:58:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:58:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:58:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4931A5EF-19CB-4D3A-ACD4-6195FBE307AC
,[ThaliCore] Session.session(_:peer:didChange:) peer:4931A5EF-19CB-4D3A-ACD4-6195FBE307AC state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77
[ThaliCore] Advertiser: session connected Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58155
,2017-07-21 10:58:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"F1wDh6jycyb9IbBavuiSq7GktuU86T09","error":null,"portNumber":58155}'
,2017-07-21 10:58:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'F1wDh6jycyb9IbBavuiSq7GktuU86T09', error: 'null', listeningPort: '58155''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-21 10:58:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 86190841-1E2B-499E-89FF-674E5A3AF1A8 (syncValue: wpUV6zzPXMPqOoV5Ks77OqWwsuqEwq7s)'
,2017-07-21 10:58:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58161
,2017-07-21 10:58:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wpUV6zzPXMPqOoV5Ks77OqWwsuqEwq7s","error":null,"portNumber":58161}'
2017-07-21 10:58:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'w,pUV6zzPXMPqOoV5Ks77OqWwsuqEwq7s', error: 'null', listeningPort: '58161''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,10:58:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 10:58:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:93A0D9D1-6F45-4D45-8431-E,C83225FE394
2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
[ThaliCore] BrowserManager.disconnect peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58155
[ThaliCore] Sess,ion.disconnect() peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:58161
[ThaliCore] Session.disconnect() peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:86190841-1E2B-499E-89FF-674E5A3AF1A8
,2017-07-21 10:58:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4931A5EF-19CB-4D3A-ACD4-6195FBE307AC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wpUV6zzPXMPqOoV5Ks77OqWwsuqEwq7s","error":"Session disconnected","portNumber":null}'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:58:09 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A,8","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:10 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77
[ThaliCore] Session.deinit peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
[ThaliCore] BrowserRelay.deinit
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'listening 58165'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'listening 58166'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:89A6591B-B21A-4818-B8BB-901F5DF7F781
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}]'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","generation":0}]'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","generation":0}'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'listening 58167'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DEEF34B0-B887-4591-BB2F-EBD8D43CDF07", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DEEF34B0-B887-4591-BB2F-EBD8D43CDF07
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DEEF34B0-B887-4591-BB2F-EBD8D43CDF07", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:DEEF34B0-B887-4591-BB2F-EBD8D43C,DF07
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:DEEF34B0-B887-4591-BB2F-EBD8D43CDF07
,[ThaliCore] Advertiser.stopAdvertising() peerID:DEEF34B0-B887-4591-BB2F-EBD8D43CDF07
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'listening 58170'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-21 10:58:13 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:13 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'listening 58171'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C361ACD3-4CCF-44CE-A31E-EB3E4C04C130
[ThaliCore] Browser.startListening
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserM,anager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DF0537B6-3C5C-4937-993B-88A8AB315ED1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DF0537B6-3C5C-4937-993B-88A8AB315ED1
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:DF0537B6-3C5C-4937-993B-88A8AB315ED1
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'listening 58174'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:25E9D04A-581C-4E1C-84C1-D16086FB4193
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A47B23B4-55C8-43A1-B383-C117634FC8BF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A47B23B4-55C8-43A1-B383-C117634FC8BF
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:A47B23B4-55C8-43A1-B383-C117634FC8BF
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10,:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'listening 58176'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:05D4EA77-A88B-4082-8C87-F400461AAE6F
[ThaliCore] Browser.startListening
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3828F0DF-0262-41BD-8047-FD11C758A77E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3828F0DF-0262-41BD-8047-FD11C758A77E
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3828F0DF-0262-41BD-8047-FD11C758A77E
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-21 10:58:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:15 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 10:58:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 10:58:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 10:58:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 10:58:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:17 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 10:58:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:18 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 10:58:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 10:58:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 10:58:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 10:58:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'listening 58179'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1012CF04-3291-42ED-8635-E9154F43A6C4
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-21 10:58:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'listening 58180'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "72270103-A774-4A6E-8DFB-BBAEFC76156D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:72270103-A774-4A6E-8DFB-BBAEFC76156D
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 272 discoveryActive matches
,ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:72270103-A774-4A6E-8DFB-BBAEFC76156D
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'listening 58182'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'listening 58183'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7C4A1A02-F49D-4C3E-811E-4DB851C48D0C
[ThaliCore] Browser.st,artListening
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}]'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","generation":0}]'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","generation":0}'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45E7D383-8196-4EB7-945B-FA5CF0BF7F6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45E7D383-8196-4EB7-945B-FA5CF0BF7F6A", generation: 0)
2017-07-21 10:58:21 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"45E7D383-8196-4EB7-945B-FA5CF0BF7F6A","generation":0}]'
2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"45E7D383-8196-4EB7-945B-FA5CF0BF7F6A","generation":0}'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"45E7D383-8196-4EB7-945B-FA5CF0BF7F6A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:21 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"45E7D383-8196-4EB7-945B-FA5CF0BF7F6A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0718B333-9577-4BCF-9755-AE8E652E9BC9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0718B333-9577-4BCF-9755-AE8E652E9BC9", generation: 0)
2017-07-21 10:58:21 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0718B333-9577-4BCF-9755-AE8E652E9BC9","generation":0}]'
2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0718B333-9577-4BCF-9755-AE8E652E9BC9","generation":0}'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0718B333-9577-4BCF-9755-AE8E652E9BC9","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:21 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0718B333-9577-4BCF-9755-AE8E652E9BC9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 10:58:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-07-21 10:58:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-21 10:58:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:22 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 10:58:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 10:58:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'listening 58185'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D9841D76-E0DD-48DA-91C5-39D5DBCF68BD
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FED086A1-5F45-4FC0-ADED-825912AED435
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","generation":0}]'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","generation":0}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:926130BD-656F-4D54-AF29-33CBA7483320:0
2017-07-21 10:58:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","connectionType":"MPCF","peerAvailable":tru,e,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B73639C,8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B73639C8-17E8-4A13-9D2F-6958AEDF8A1C (syncValue: VcP2wkj75Yq9cT50GV0TZIpc9ObU4ZZA)'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7,3639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7,483320","generation":0}]'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","generation":0}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:24 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:800238E4-725F-4663-8820-A044C868E9BB
[ThaliCore] Advertiser: session connected Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:800238E4-725F-4663-8820-A044C868E9BB state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58188
,2017-07-21 10:58:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VcP2wkj75Yq9cT50GV0TZIpc9ObU4ZZA","error":null,"portNumber":58188}'
,2017-07-21 10:58:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VcP2wkj75Yq9cT50GV0TZIpc9ObU4ZZA', error: 'null', listeningPort: '58188''
,2017-07-21 10:58:28 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [9, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:58:28 - DEBUG testUtils: 'Got response data'
,2017-07-21 10:58:28 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:800238E4-725F-4663-8820-A044C868E9BB
,[ThaliCore] Session.session(_:peer:didChange:) peer:800238E4-725F-4663-8820-A044C868E9BB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:800238E4-725F-4663-8820-A044C868E9BB
,[ThaliCore] Session.startOutputStream(with:) peer:800238E4-725F-4663-8820-A044C868E9BB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [9, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FED086A1-5F45-4FC0-ADED-825912AED435
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 285 must be stopped
[ThaliCore] B,rowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Doma,in=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnect,Handler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[Thal,iCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [9, 12]
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:800238E4-725F-4663-8820-A044C868E9BB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:800238E4-725F-4663-8820-A044C868E9BB
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [9]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserManager.disconnect peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58188
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VcP2wkj75Yq9cT50GV0TZIpc9ObU4ZZA","error":"Session disconnected","portNumber":null}'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:800238E4-725F-4663-8820-A044C868E9BB
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:31 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-21 10:58:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:32 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 10:58:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-21 10:58:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:58:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:58:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"45E7D383-8196-4EB7-945B-FA5CF0BF7F6A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:58:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0718B333-9577-4BCF-9755-AE8E652E9BC9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:58:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:58:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 292 error should be null
,ok 293 error should be null
,# setup
,ok 294 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 295 specific error should be returned
,# teardown
,ok 296 error should be null
,ok 297 error should be null
,# setup
,ok 298 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'listening 58191'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:33 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
,ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'listening 58192'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BDFA32C2-27E0-49DB-82A9-ABFAE23804DD
[ThaliCore] Browser.st,artListening
2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
,ok 309 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:926130BD-656F-4D54-AF29-33CBA7483320:0
2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","generation":0}]'
2017-07-21 10:58:34 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","generation":0}'
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:58:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 10:58:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'listening 58193'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F4F711BD-826A-4B1E-B849-CA0B23AED6B8", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:F4F711BD-826A-4B1E-B849-CA0B23AED6B8
2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F4F711BD-826A-4B1E-B849-CA0B23AED6B8", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:F4F711BD-826A-4B1E-B849-CA0B23AED6B8
20,17-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F4F711BD-826A-4B1E-B849-CA0B23AED6B8
,[ThaliCore] Advertiser.stopAdvertising() peerID:F4F711BD-826A-4B1E-B849-CA0B23AED6B8
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'listening 58196'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 320 error should be null
ok 321 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
,ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 10:58:35 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
,ok 328 native router should be bad
,# teardown
,ok 329 error should be null
,ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'listening 58197'
ok 332 first call should succeed
ok 333 first call should succeed
,ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
,ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 10:58:36 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 10:58:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
,ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 10:58:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cc363548-1503-4a91-a21b-025e2bec93bd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 344 should be called once
,ok 345 should not have been called more than once
,# teardown
,2017-07-21 10:58:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cc363548-1503-4a91-a21b-025e2bec93bd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"461f1d1e-a789-4f5f-a64c-38b91656858f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 354 peer should be available
,ok 355 cache contains native peer
,2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"461f1d1e-a789-4f5f-a64c-38b91656858f","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 356 peer should be unavailable
,ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
,ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5e1147fc-9cc2-4f67-87cf-3eaacf1f0294","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 362 peer should be available
ok 363 cache contains wifi peer
,2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5e1147fc-9cc2-4f67-87cf-3eaacf1f0294","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 364 peer should be unavailable
,ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
,ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5812de53-1c98-4a6e-9ed0-54d651bbada9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 369 first peer is a,vailable
2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"71475b4d-f3df-422a-ba63-efac0a287def","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 370 second, peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5812de53-1c98-4a6e-9ed0-54d651bbada9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"71475b4d-f3df-422a-ba63-efac0a287def","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
,ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
,2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b8a62b9f-1e45-4e6c-927f-11143729ced0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 376 peer is available
,# teardown
,2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b8a62b9f-1e45-4e6c-927f-11143729ced0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
,ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 10:58:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
,ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 10:58:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1a166441-094a-4a50-8982-1cc5837e52b5","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be available
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1a166441-094a-4a50-8982-1cc5837e52b5","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be ,available
ok 388 should store correct generation
,# teardown
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1a166441-094a-4a50-8982-1cc5837e52b5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 10:58:39 - DEBUG thaliMobileNativeWrapper: 'listening 58198'
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c41dfd6e-d3be-4f5b-8d2c-c05b14f68590","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c41dfd6e-d3be-4f5b-8d2c-c05b14f68590","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,# teardown
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c41dfd6e-d3be-4f5b-8d2c-c05b14f68590","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'listening 58199'
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"90339dc6-eaa0-472a-92ee-49a2fd2b7c1a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 399 discovered available peer
,ok 400 peer is available
,# teardown
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"90339dc6-eaa0-472a-92ee-49a2fd2b7c1a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
,ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3d47d5e1-34ce-4023-86d2-a169fb7f6595","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 404 peer should be available
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3d47d5e1-34ce-4023-86d2-a169fb7f6595","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 405 peer should be unavailable
,ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
,ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'listening 58200'
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"adc58ed9-d51f-4562-814e-8f0845557370","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 410 first peer is expected to be available
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b95358b7-2482-431c-8c8b-e68e564553d4","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 411 second peer is expected to be available
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b95358b7-2482-431c-8c8b-e68e564553d4","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 412 peer became unavailable
,ok 413 it was wifi peer
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b95358b7-2482-431c-8c8b-e68e564553d4","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b95358b7-2482-431c-8c8b-e68e564553d4","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"adc58ed9-d51f-4562-814e-8f0845557370","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 10:58:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
,ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 10:58:41 - DEBUG thaliMobileNativeWrapper: 'listening 58201'
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6a922174-7ec7-4bb2-bd2e-61ecaddb6ebd","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 424 first peer is expected to be available
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1b0abb78-2b1f-441a-906c-79d641d4c60b","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 425 second peer is expected to be available
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6a922174-7ec7-4bb2-bd2e-61ecaddb6ebd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1b0abb78-2b1f-441a-906c-79d641d4c60b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 10:58:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 10:58:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
,ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"205f2e70-6df6-44e7-9d4d-8835675b28c0","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 peer discovered first time does not have new address
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"205f2e70-6df6-44e7-9d4d-8835675b28c0","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 438 address has not been changed
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"205f2e70-6df6-44e7-9d4d-8835675b28c0","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 439 new port handled correctly
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"205f2e70-6df6-44e7-9d4d-8835675b28c0","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 440 new host handled correctly
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"205f2e70-6df6-44e7-9d4d-8835675b28c0","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
,ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 10:58:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 445 error should be null
ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 448 NOT IMPLEMENTED # SKIP
,# teardown
,ok 449 error should be null
ok 450 error should be null
,# setup
,ok 451 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-21 10:58:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 452 error should be null
,ok 453 error should be null
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
,2017-07-21 10:58:43 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 contains expected properties
,ok 463 the same hostAddress
,ok 464 the same portNumber
,# teardown
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
,ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 468 contains expected properties
ok 469 the same hos,tAddress
ok 470 the same portNumber
,# teardown
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
,ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 10:58:44 - DEBUG thaliMobileNativeWrapper: 'listening 58202'
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f6dfa2c7-9d01-4c51-893e-94c0c4896dad","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 474 Got specific error message
,# teardown
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f6dfa2c7-9d01-4c51-893e-94c0c4896dad","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 10:58:44 - DEBUG thaliMobileNativeWrapper: 'listening 58203'
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9e68329d-bcb7-41b0-937f-d5929a9ca1f6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:9e68329d-bcb7-41b0-937f-d5929a9ca1f6
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 10:58:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9e68329d-bcb7-41b0-937f-d5929a9ca1f6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
,ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
,ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 10:58:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 10:58:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
,ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 10:58:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'listening 58204'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4E231231-90CC-4E9D-83C7-675239233133
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2a590a85-eb55-48d8-966f-fe853504caa0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"16cc67e3-4579-476e-b8fc-85619311a73f","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2a590a85-eb55-48d8-966f-fe853504caa0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"16cc67e3-4579-476e-b8fc-85619311a73f","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 10:58:47 - DEBUG thaliMobileNativeWrapper: 'listening 58205'
,2017-07-21 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f0680168-8c3d-4d6f-b8e2-45861b00ae72","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 1
,ok 513 2
,2017-07-21 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d14b8816-3a36-4dc5-84de-90e7fe3556b2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f0680168-8c3d-4d6f-b8e2-45861b00ae72","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d14b8816-3a36-4dc5-84de-90e7fe3556b2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-21 10:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 514 error should be null
,ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 10:58:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
,ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'listening 58206'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE,6FCF46417D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D
2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 522 error should be null
ok 523 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159
[ThaliCore] Browser.startListening
2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:926130BD-656F-4D54-AF29-33CBA7483320:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"926130BD-656F-4D54-AF,29-33CBA7483320","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","generation":0}'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","generation":0}]'
2017-07-21 10:58:48 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","generation":0}'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 926130BD-656F-4D54-AF29-33CBA7483320 (syncValue: 0)'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:926130BD-656F-4D54-AF29-33CBA7483320:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4CDF9656-B658-49DA-B347-1BEC9558B984", generation: 0)
2017-07-21 10:58:49 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4CDF9656-B658-49DA-B347-1BEC9558B984","generation":0}]'
2017-07-21 10:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4CDF9656-B658-49DA-B347-1BEC9558B984","generation":0}'
,2017-07-21 10:58:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4CDF9656-B658-49DA-B347-1BEC9558B984","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:49 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4CDF9656-B658-49DA-B347-1BEC9558B984","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67A4F3A2-48D4-4914-A36B-20CC0B58C4CA", generation: 0)
,2017-07-21 10:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"67A4F3A2-48D4-4914-A36B-20CC0B58C4CA","generation":0}]'
,2017-07-21 10:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"67A4F3A2-48D4-4914-A36B-20CC0B58C4CA","generation":0}'
,2017-07-21 10:58:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67A4F3A2-48D4-4914-A36B-20CC0B58C4CA","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67A4F3A2-48D4-4914-A36B-20CC0B58C4CA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:926130BD-656F-4D54-AF29-33CBA7483320:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:92,6130BD-656F-4D54-AF29-33CBA7483320:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,26130BD-656F-4D54-AF29-33CBA7483320", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:926130BD-656F-4D54-AF29-33CBA7483320:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:926130BD-656F-4D54-AF29-33CBA7483320:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:926130BD-656F-4D54-AF29-33CBA7483320:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","generation":0}]'
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
,2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","generation":0}'
,2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 10:58:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","generation":0}]'
,2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","generation":0}'
,2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 10:58:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:926130BD-656F-4D54-AF29-33CBA7483320:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:92,6130BD-656F-4D54-AF29-33CBA7483320:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,26130BD-656F-4D54-AF29-33CBA7483320", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,1 10:58:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:58:54 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B73639C8-17E8-4A13-9D2F-6958AEDF8A1C (syncValue: 1)'
2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", ge,neration: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E
[ThaliCore] Advertiser: session connected Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E state: notConnected -> connecting
[ThaliCore] Session.deinit peer:926130BD-656F-4D54-AF29-33CBA7483320:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":"Peer is unava,ilable","portNumber":null}'
2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-2,1 10:58:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 10:58:54 - DEBUG thaliMobileNativeWra,pper: 'Issuing multiConnect for 4CDF9656-B658-49DA-B347-1BEC9558B984 (syncValue: 2)'
,2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4CDF9656-B658-49DA-B347-1BEC9558B984", generation: 0) creating a new relay
[ThaliCo,re] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4CDF9656-B658-49DA-B347-1BEC9558B984", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E
,[ThaliCore] Session.session(_:peer:didChange:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4CDF9656-B658-49DA-B347-1BEC9558B984", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58214
,2017-07-21 10:58:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":58214}'
,2017-07-21 10:58:56 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 67A4F3A2-48D4-4914-A36B-20CC0B58C4CA (syncValue: 3)'
,2017-07-21 10:58:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "67A4F3A2-48D4-4914-A36B-20CC0B58C4CA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67A4F3A2-48D4-4914-A36B-20CC0B58C4CA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E
[ThaliCore] Session.startOutputStream(with:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [9, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [9, 14, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:58:57 - DEBUG testUtils: 'Got response data'
,2017-07-21 10:58:57 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF
[ThaliCore] Advertiser: session connected Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "67A4F3A2-48D4-4914-A36B-20CC0B58C4CA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58219
2017-07-21 10:59:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":58219,}'
,[ThaliCore] BrowserManager.disconnect peer:926130BD-656F-4D54-AF29-33CBA7483320
,[ThaliCore] BrowserManager.disconnect peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67A4F3A2-48D4-491,4-A36B-20CC0B58C4CA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [9, 14, 15, 16]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:59:00 - DEBUG testUtils: 'Got response data'
,2017-07-21 10:59:00 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF
,[ThaliCore] Session.session(_:peer:didChange:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF
,[ThaliCore] Session.startOutputStream(with:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [9, 14, 15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 10:59:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4CDF9656-B658-49DA-B347-1BEC9558B984","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:59:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"67A4F3A2-48D4-4914-A36B-20CC0B58C4CA","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D
,2017-07-21 10:59:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:59:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 10:59:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:59:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:59:02 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:59:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 527 error should be null
ok 528 error should be null
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDe,scription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler remove,d virtual socket vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeS,treams() vsID:17
,# setup
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [9, 15, 16, 17]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStrea,msHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [9, 15, 16]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [9, 15]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket erro,r:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 529 ThaliMobile should be stopped
,# test for data corruption
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [9]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:ni,l
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 10:59:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 530 error should be null
ok 531 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 532 getPeerIdentifier
ok 533 getConnectionType
ok 534 getActionType
ok 535 getActionState
ok 536 getPskIdentity
ok 537 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 538 initial state
ok 539 after start
2017-07-21 10:59:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 10:59:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 542 clean kill
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
ok 548 agent is destroyed
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
ok 586 enqueue is fine
ok 587 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 588 is an agent
ok 589 first enqueue is fine
ok 590 is an agent
,ok 591 second enqueue is fine
,ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
,ok 595 good enqueue
,ok 596 Identity should match
,2017-07-21 10:59:09 - DEBUG testUtils: 'Got response data'
,2017-07-21 10:59:09 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-21 10:59:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 609 good enqueue
,ok 610 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 611 null arg
,ok 612 wrong arg type
,ok 613 wrong arg type
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
,ok 624 first kill
,ok 625 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 626 1st good enqueue
ok 627 2nd good enqueue
ok 628 1st action is in the pool
ok 629 2nd action is in the pool
ok 630 1st action is out of the pool
,ok 631 2st action is out of the pool
ok 632 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-21 10:59:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 633 Got right error
ok 634 Start should not be called
ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 10:59:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 10:59:12 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 636 Got right error
,ok 637 Start should not be called
,ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 639 Got null
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 640 is an agent
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 642 Got Null
,ok 643 Got another null
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 644 is an agent
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 649 should have gotten null
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 650 Should have stopped nicely
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 654 Null 1
ok 655 (unnamed assert)
2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBlu,etooth, Peer Identifier: notificationAction'
ok 656 is an agent
,ok 657 Null 3
ok 658 Replication not yet called
ok 659 Notification 2 not yet called
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 666 is an agent
,ok 667 First does not throw
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 668 is an agent
,ok 669 Second does not throw
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 first ok
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-21 10:59:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-21 10:59:16 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
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
,2017-07-21 10:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 10:59:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-21 10:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
,ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 10:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
ok 686 correct error message
,# teardown
,2017-07-21 10:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-07-21 10:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
,ok 691 Start after killed
,# teardown
,2017-07-21 10:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-07-21 10:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-21 10:59:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-07-21 10:59:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 10:59:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 698 Should be NETWORK_PROBLEM caused closing server socket
,ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-21 10:59:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 702 publicKeysToNotify cannot be null
,ok 703 ecdh for local device cannot be null
,ok 704 milliseconds cannot be less than 0
,ok 705 milliseconds cannot be 0
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
,2017-07-21 10:59:30 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 719 should be equal
,ok 720 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 721 right number of calls to address book
,ok 722 good preAmble
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
ok 729 keys match
,ok 730 secrets match
,ok 731 We have an entry!
ok 732 keys match
,ok 733 secrets match
,ok 734 We have an entry!
ok 735 keys match
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
,ok 744 tcp peer's notification has correct connection type
,2017-07-21 10:59:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 10:59:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 10:59:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
,2017-07-21 10:59:34 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-07-21 10:59:34 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 10:59:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
ok 748 entry is resolved
,# teardown
,2017-07-21 10:59:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
,ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-21 10:59:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
ok 752 portNumber must match
ok 753 suggestedTCPTimeout must match
ok 754 connectionType must match
ok 755 peerIDs must match
,# teardown
,2017-07-21 10:59:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-21 10:59:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-21 10:59:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 10:59:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 10:59:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 10:59:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 10:59:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 765 action should be resolved with NETWORK_PROBLEM error
,ok 766 correct number of requests
,ok 767 correct number of failures
,ok 768 correct final peer state
,# teardown
,2017-07-21 10:59:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 10:59:40 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 10:59:40 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-07-21 10:59:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 10:59:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
,ok 771 peer state should be RESOLVED
,# teardown
,2017-07-21 10:59:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 10:59:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
# teardown
,2017-07-21 10:59:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-21 10:59:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-21 10:59:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-21 10:59:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-21 10:59:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 10:59:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-07-21 10:59:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 10:59:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 10:59:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
,ok 798 should be 200
,ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
ok 803 should be 204
,# teardown
,2017-07-21 10:59:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
,ok 805 should be 204
,# teardown
,2017-07-21 10:59:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-07-21 10:59:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
ok 808 not equal connection type
ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 10:59:52 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-21 10:59:52 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-21 10:59:53 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-21 10:59:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-21 10:59:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 10:59:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:59:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 10:59:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-21 10:59:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 10:59:54 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 10:59:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-07-21 10:59:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-21 10:59:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-21 10:59:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 10:59:56 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 10:59:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-21 10:59:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 10:59:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 10:59:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 11:00:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-21 11:00:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 11:00:03 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 11:00:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 11:00:06 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-21 11:00:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 11:00:07 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 11:00:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 11:00:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-21 11:00:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 11:00:11 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 11:00:12 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-21 11:00:13 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 11:00:13 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 860 action should be killed
,ok 861 Error should be timed out
,# teardown
,2017-07-21 11:00:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-21 11:00:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
,ok 864 Same pouchdB
,ok 865 same localDbName
,ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 11:00:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'listening 58347'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] Browser.startListening
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A4194BA7-1EB2-4E58-9EE4-605A14B2387A
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6B4B658-9B6C-4365-A441-47A5119A6F4B", generation: 0)
2017-07-21 11:00:17 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C6B4B658-9B6C-4365-A441-47A5119A6F4B","generation":0}]'
2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C6B4B658-9B6C-4365-A441-47A5119A6F4B","generation":0}'
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C6B4B658-9B6C-4365-A441-47A5119A6F4B","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 11:00:17 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C6B4B658-9B6C-4365-A441-47A5119A6F4B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for C6B4B658-9B6C-4365-A441-47A5119A6F4B (syncValue: 4)'
2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C6B4B658-9B6C-4365,-A441-47A5119A6F4B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C6B4B658-9B6C-4365-A441-47A5119A6F4B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "667385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0)
,2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"667385B3-84B4-4AAD-A98D-31F23F247C31","generation":0}]'
,2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"667385B3-84B4-4AAD-A98D-31F23F247C31","generation":0}'
,2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"667385B3-84B4-4AAD-A98D-31F23F247C31","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 11:00:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"667385B3-84B4-4AAD-A98D-31F23F247C31","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] Advertiser: session connected Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Advertiser: session connected Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C6B4B658-9B6C-4365-A441-47A5119A6F4B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58350
,2017-07-21 11:00:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":58350}'
,2017-07-21 11:00:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 667385B3-84B4-4AAD-A98D-31F23F247C31 (syncValue: 5)'
2017-07-21 11:00:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "667385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66,7385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [9, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [9]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [9, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 11:00:22 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [9, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [9, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [9, 19, 20, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [9, 19, 20, 21, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [9, 19, 20, 21, 23]
,2017-07-21 11:00:22 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "667385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58359
2017-07-21 11:00:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":58359,}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [9, 19, 20, 21, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] Sessio,n.session(_:peer:didChange:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01 state: connecting -> connected
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] VirtualSocket.deinit vsID:24 [9, 19, 20, 21, 23]
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,5 [9, 19, 20, 21, 23, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [9, 19, 20, 21, 23, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
,[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [9, 19, 20, 21, 23, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 11:00:24 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [9, 19, 20, 21, 23, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [9, 19, 20, 21, 23, 25, 26, 27, 28, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36 state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [9, 19, 20, 21, 23, 25, 26, 27, 28, 29, 30]
[ThaliCore] BrowserRelay.didOpenVirtual,SocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
,[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [9, 19, 20, 21, 23, 25, 26, 27, 28, 29, 30, 31]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:31 [9, 19, 20, 21, 23, 25, 26, 27, 28, 29, 30]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 11:00:24 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [9, 19, 20, 21, 23, 25, 26, 27, 28, 29, 30, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 11:00:24 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [9, 19, 20, 21, 23, 25, 26, 27, 28, 29, 30, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [9, 19, 20, 21, 23, 25, 26, 27, 28, 29, 30, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [9, 19, 20, 21, 23, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [9, 19, 20, 21, 23, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35, 36]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-21 11:00:25 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [9, 19, 20, 21, 23, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-21 11:00:25 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 11:00:25 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [9, 20, 21, 23, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35, 36, 37]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:20
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:20 [9, 21, 23, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35, 36, 37]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [9, 23, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35, 36, 37]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [9, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35, 36, 37]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [9, 25, 26, 27, 28, 29, 30, 32, 33, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,8 [9, 25, 26, 27, 28, 29, 30, 32, 33, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [9, 25, 26, 27, 28, 29, 30, 32, 33, 35, 36, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
,[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [9, 25, 26, 27, 28, 29, 30, 32, 33, 35, 36, 37, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [9, 25, 26, 27, 28, 29, 30, 32, 33, 35, 36, 37, 38, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 11:00:26 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 11:00:26 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:28
[ThaliCore] TCPListener.socketDidDi,sconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) ac,cepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliC,ore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] VirtualSocket.deinit vsID:26 [9, 25, 27, 28, 29, 30, 32, 33, 35, 36, 37, 38, 40]
[ThaliCore] BrowserRelay.didS,ocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.deinit vsID:28 [9, 25, 27, 29, 30, 32, 33, 35, 36, 37, 38, 40]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [9, 25, 27, 29, 32, 33, 35, 36, 37, 38, 40]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [9, 25, 27, 29, 32, 33, 36, 37, 38, 40]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [9, 25, 29, 32, 33, 36, 37, 38, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_,:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream e,ndEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] VirtualSocket.handleEventOnInputStream endEnco,untered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [9, 25, 32, 33, 36, 37, 38, 40]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [9, 25, 32, 36, 37, 38, 40]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:37 [9, 25, 32, 36, 38, 40]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [9, 25, 36, 38, 40]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [9, 25, 38, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:,) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:38 [9, 25, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [9, 25]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client, disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 11:03:17 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-21 11:03:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-21 11:10:16 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-21 11:10:17 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-21 11:10:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 867 failed with TimeoutError
,  ---
,    operator: fail
,  ...
,# teardown
,2017-07-21 11:10:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4,995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:14:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:14:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:14:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-499,5-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:14:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0A8A42F4-ADF0-4995-8335-EE17139F4BC1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
