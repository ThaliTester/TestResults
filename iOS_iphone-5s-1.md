#### Test 1459176191a53731_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1459176191a53731/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/74D397A2-12DD-4EEF-B923-066141BD7C96/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/74D397A2-12DD-4EEF-B923-066141BD7C96/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1459176191a53731/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1459176191a53731/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52452"
,(lldb)     command script import "/tmp/74D397A2-12DD-4EEF-B923-066141BD7C96/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready
,JXcore engine is started
,2017-10-12 14:07:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:07:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:07:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:07:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:07:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:07:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:07:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A19EA419-0F5F-4CE6-A39E-1E34FD86E113", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A19EA419-0F5F-4CE6-A39E-1E34FD86E113
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:583CFEF9-96F9-4E13-A11B-EF7B6A86F615
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:66AA0CA6-,42FD-4088-A2AA-E733B710ACC3
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8A2474BC-BA36-4F8D-9A15-99556B40159F", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:8A2474BC-BA36-4F8D-9A15-99556B40159F
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A2474BC-BA36-4F8D-9A15-99556B40159F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A2474BC-BA36-4F8D-9A15-99556B40159F", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-10-12 14:07:41 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.560979008674622
,2017-10-12 14:07:41 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-10-12 14:07:41 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8A2474BC-BA36-4F8D-9A15-99556B40159F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8A2474BC-BA36-4F8D-9A15-99556B40159F", generation: 0)
,2017-10-12 14:07:45 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-10-12 14:07:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-10-12 14:07:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-10-12 14:07:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-10-12 14:07:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-10-12 14:07:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-10-12 14:07:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-10-12 14:07:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-10-12 14:07:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-10-12 14:07:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-10-12 14:07:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-10-12 14:07:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-10-12 14:07:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-10-12 14:07:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-10-12 14:07:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-10-12 14:07:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-10-12 14:07:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-10-12 14:07:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-10-12 14:07:49 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-10-12 14:07:49 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-10-12 14:07:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:08:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:08:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:08:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:08:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:08:30 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-10-12 14:08:30 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-10-12 14:08:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-10-12 14:08:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-10-12 14:08:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-10-12 14:08:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-10-12 14:08:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-10-12 14:08:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-10-12 14:08:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-10-12 14:08:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
,ok 5 should be equal
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
,2017-10-12 14:08:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-10-12 14:08:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-10-12 14:08:54 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-10-12 14:08:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:08:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-10-12 14:08:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BC2689EA-F51C-492A-AED6-EE82C4F42578
[ThaliCore] Browser.startListening
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:08:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:09:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:455AE19E-AA44-43C5-B84E-0CAB161632E0
[ThaliCore] Browser.startListening
,2017-10-12 14:09:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:09:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 64 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:09:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:09:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:02 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:09:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:04 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:09:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "13813B75-1DFC-489A-9913-4EDC2843B2FA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:13813B75-1DFC-489A-9913-4EDC2843B2FA
2017-10-12 14:09:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:07, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-10-12 14:09:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Adve,rtiser.stopAdvertising() peerID:13813B75-1DFC-489A-9913-4EDC2843B2FA
2017-10-12 14:09:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:07 - INFO thaliMobil,e,: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "647DBE1F-54A4-4C15-9212-CEA4364A8570", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:647DBE1F-54A4-4C15-9212-CEA4364A8570
2017-10-12 1,4:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "647DBE1F-54A4-4C15-9212-CEA4364A8570", generation: 1)
[ThaliCore] ,Advertiser.startAdvertising with peerID:647DBE1F-54A4-4C15-9212-CEA4364A8570
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:09:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:09:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:647DBE1F-54A4-4C15-9212-CEA4364A8570
,[ThaliCore] Advertiser.stopAdvertising() peerID:647DBE1F-54A4-4C15-9212-CEA4364A8570
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3806CC5D-8F7F-45C0-B357-1E5F3C9E873D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3806CC5D-8F7F-45C0-B357-1E5F3C9E873D
2017-10-12 1,4:09:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7994DA75-C171-4FC4-BFB4-581D1D601F76
[Thali,Core] Browser.startListening
2017-10-12 14:09:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:09:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:11 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3806CC5D-8F7F-45C0-B357-1E5F3C9E873D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3806CC5D-8F7F-45C0-B357-1E5F3C9E873D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A4FF9A1-67A7-4775-8320-CFA8061C113C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A4FF9A1-67A7-4775-8320-CFA8061C113C", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CE7BB6E-C82C-4C8F-B9DB-C90F6B8C394F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CE7BB6E-C82C-4C8F-B9DB-C90F6B8C394F", generation: 0)
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3806CC5D-8F7F-45C0-B357-1E5F3C9E873D
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,anged registered to native'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7A795224-AA94-44DF-BB33-0C1B76A830D2
,2017-10-12 14:09:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:09:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:09:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:69CE5C4D-7A96-40EA-B08E-72F219D6EECD
[ThaliCore] Browser.startListening
,2017-10-12 14:09:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:09:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-10-12 14:09:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
2017-10-12 14:09:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1E35A50E-3E8B-4739-963D-88DB705300A6","generation":0}'
,2017-10-12 14:09:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1E35A50E-3E8B-4739-963D-88DB705300A6 (syncValue: JDDdYDprtfpAuXZGNTLKagIr3TfY2yam)'
,2017-10-12 14:09:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:09:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AF5469F9-24AD-4DE5-8938-C5288B08F245","generation":0}'
,2017-10-12 14:09:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50561
2017-10-12 14:09:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JDDdYDprtfpAuXZGNTLKagIr3TfY2yam","error":null,"portNumber":50561}'
,2017-10-12 14:09:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JDDdYDprtfpAuXZGNTLKagIr3TfY2yam', error: 'null', listeningPort: '50561''
,2017-10-12 14:09:28 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-10-12 14:09:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 ,14:09:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7A795224-AA94-44DF-BB33-0,C1B76A830D2
2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:1E35A50E-3E8B-4739-963D-88DB705300A6
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50561
[ThaliCore] Session.disconnect() p,eer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
,[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4
2017-10-12 1,4:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CDC4C3D7-011E-4441-AA4D-651A44459395
[Thal,i,Core] Browser.startListening
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:09:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
2017-10-12 14:09:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AF5469F9-24AD-4DE5-8938-C5288B08F245","generation":0}'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AF5469F9-24AD-4DE5-8938-C5288B08F245, (syncValue: 11BN852BNlASKqqxT16bPI8XiZCOUgdI)'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B0,8F245", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found ,peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPLis,tener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"1E35A50E-3E8B-4739-963D-88DB705300A6","generation":0}'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
,2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"780BD97C-6130-4480-B34B-311832BCA220","generation":0}'
,2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:27902114-8768-484E-9050-1BAE80B6CED9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "27902114-8768-484E-9050-1BAE80B6CED9", generation: 0)
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"27902114-8768-484E-9050-1BAE80B6CED9","generation":0}'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AF,5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,F5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AF,5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,F5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AF,5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,F5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AF,5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:AF5469F9,-24AD-4DE5-8938-C5288B08F245 error: max retries exceeded
2017-10-12 14:09:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11BN852BNlASKqqxT16bPI8XiZCOUgdI","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '11BN852BNlASKqqxT16bPI8XiZCOUgdI', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:09:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 780BD97C-6130-4480-B34B-311832BCA220 (syncValue: teU8tqjvoPg4EKQrskL024cT6B1Xa3Fw)'
,2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3347533E-2456-4380-92DD-7C9D11C4A7E5
[ThaliCore] Advertiser: session connected Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3347533E-2456-4380-92DD-7C9D11C4A7E5 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:780BD97C-6130-4480-B34B-311832BCA220:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:780BD97C-6130-4480-B34B-311832BCA220:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50568
,2017-10-12 14:09:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"teU8tqjvoPg4EKQrskL024cT6B1Xa3Fw","error":null,"portNumber":50568}'
,2017-10-12 14:09:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'teU8tqjvoPg4EKQrskL024cT6B1Xa3Fw', error: 'null', listeningPort: '50568''
,Connecting to the localhost:50568
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
Connected to the localhost:50568
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:1
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:20 count:1 vsID:1
,[ThaliCore] VirtualSocket.writePendingData() to write:20 written:20 count:0 vsID:1
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:1
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 20 vsID:1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3347533E-2456-4380-92DD-7C9D11C4A7E5
,ok 88 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] Session.session(_:peer:didChange:) peer:3347533E-2456-4380-92DD-7C9D11C4A7E5 state: connecting -> connected
,# teardown
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3347533E-2456-4380-92DD-7C9D11C4A7E5
,[ThaliCore] Session.startOutputStream(with:) peer:3347533E-2456-4380-92DD-7C9D11C4A7E5
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 20 vsID:2
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:20 count:1 vsID:2
,[ThaliCore] VirtualSocket.writePendingData() to write:20 written:20 count:0 vsID:2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:2
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:3347533E-2456-4380-92DD-7C9D11C4A7E5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3347533E-2456-4380-92DD-7C9D11C4A7E5
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:780BD97C-6130-4480-B34B-311832BCA220:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:50568
[ThaliCore] Session.disconnect() peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"teU8tqjvoPg4EKQrskL024cT6B1Xa3Fw","error":"Session disconnected","portNumber":null}'
,2017-10-12 14:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 ,14:09:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-12 14:09:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:926E3705-DB20-4BDE-A6DB-E,3E0E96DA5C4
2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:780BD97C-6130-4480-B34B-311832BCA220
2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD
2017-10-12 1,4:09:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF
[Thali,Core] Browser.startListening
2017-10-12 14:09:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:09:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-10-12 14:09:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
[ThaliCore] Session.deinit peer:780BD97C-6130-4480,-B34B-311832BCA220:0
,[ThaliCore] Session.deinit peer:3347533E-2456-4380-92DD-7C9D11C4A7E5
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
,2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"780BD97C-6130-4480-B34B-311832BCA220","generation":0}'
,2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 780BD97C-6130-4480-B34B-311832BCA220 (syncValue: OpkCNY2qBNoUBgBCuJGAdwymV4HkJAyr)'
,2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
2017-10-12 14:09:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BBF9DB54-27C0-4C93-909E-CE62E7FD08F3","generation":0}'
2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:09:50 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
2017-10-12 14:09:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D5CF258-9502-47E8-8BC3-9388881E8557","generation":0}'
2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:780BD97C-6130-4480-B34B-311832BCA220:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,0BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,80BD97C-6130-4480-B34B-311832BCA220", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:780BD97C-6130-4480-B34B-311832BCA220:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,0BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,80BD97C-6130-4480-B34B-311832BCA220", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:09:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OpkCNY2qBNoUBgBCuJGAdwymV4HkJAyr","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:09:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OpkCNY2qBNoUBgBCuJGAdwymV4HkJAyr', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:09:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:09:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BBF9DB54-27C0-4C93-909E-CE62E7FD08F3 (syncValue: 1xjnB9mnd612WEdVEvrZHbh,hXVFsDErp)'
2017-10-12 14:09:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BBF9DB54-27C0-4C93-909E-CE62E,7FD08F3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:09:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50581
,2017-10-12 14:09:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1xjnB9mnd612WEdVEvrZHbhhXVFsDErp","error":null,"portNumber":50581}'
,2017-10-12 14:09:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1xjnB9mnd612WEdVEvrZHbhhXVFsDErp', error: 'null', listeningPort: '50581''
,Connecting to the localhost:50581
,Connecting to the localhost:50581
Connecting to the localhost:50581
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:BBF9DB54-27C0-4C93-909E-CE62,E7FD08F3:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
,Connected to the localhost:50581
Connected to the localhost:50581
Connected to the localhost:50581
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 3]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 3, 4]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-10-12 14:09:58 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:3
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:3
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:3
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:3
,ok 92 correct string length
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:4
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:4
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
,ok 93 correct string length
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:5
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:5
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:3 [1, 4, 5]
,ok 94 got the same data back
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1663 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:4
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [1, 5]
,ok 95 got the same data back
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 3285 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2149 vsID:5
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1]
,ok 96 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0
[ThaliCore] Advertiser: session connected Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0
[ThaliCore] Session.startOutputStream(with:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [1, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0
[ThaliCore] Session.startOutputStream(with:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.startOutputStream(with:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:6
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:7
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server received (8192 bytes):'
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server received (8192 bytes):'
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:7
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:7
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:7
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:8
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [1, 6, 8]
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:8
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server received (8192 bytes):'
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:,6
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:6
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:6
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [1, 8]
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server received (8192 bytes):'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:,8
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:8
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:8
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [1]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1
[ThaliCore] Advertiser: session connected Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1
,[ThaliCore] Session.session(_:peer:didChange:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1
[ThaliCore] Session.startOutputStream(with:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [1, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1
[ThaliCore] Session.startOutputStream(with:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1
[Tha,liCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:9
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:10
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1
[ThaliCore] Session.startOutputStream(with:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 9, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:9
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:9
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:10
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:10
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:10
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:11
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:10
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:11
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received all data: D3jM5M8rYn1dQviElIoky2aEMbJBy3shRrzqstEniTD3GM8zf7vcTiUxrpROaAdczWzzI1uf0heuKbvt3equ3PDCbdvwPjldPprcBE6nrQy7fPRqRRnfMYe9G92JvMFst25jXg57CFqPmxNmnvrkZ0u31aTqLoZ8WWfW0uplG8yLhPmJvM,1V5nVY9HbI9ZnhUYhGEfF1ajCUdXDw0SeafbRByEI74Tftyn5XONXg7Mg0LEKXQCfvirnvNjVBEoVsiTXcadDhTbGuAtLCSXnOg0o5vqRlj2IBqmeW4eOiNLYpsckmNpQAx247F5aphWgxD9qoM1UV0D9V19RnWx6DUwg0WyNaIUeVBTxchxgF6JJaB16KiyXQG0Qqx0WFc6ngjTTvYuYgAekfUW5vTE9VVRfbF26LiogP4KBHlyRI60EOuDjj0C,VgzFt9sSOdQqeU67RZ3Gn0kc5Q5CrgCND3EvgdDVwj3E7YsemKMEf7aIv0eGDp4DtAJgccqtDmZMeAeYuZ1s0ThVLQZRjrULcMvKkNX0pf4ao9R6QmdTPVlYFHC2fUvnU3RyoNHarKkJmW8ACO2qvBKJhuMrGuZxX9ClMPcVFxc8KyNir5so5dR2uhwBOpu78Xqi0Ahkxywvo8ZRN2OB1B0woEi4KanGTcNWayF1QIUof5VyLFQOggBfgCGWosGI,OvazHyfSygTf1ZWrYzCa25ebuJFKzDBYB6HqTtXEM4Nu4RXiZzH787YHoLo6NNMWIxlUmajk2Q0idRuQUC3CXrB0eyzXoYkgGuM7iN5JcLVCvYWQBFxLgSfXyufYLJzyfvVCsGxe89EB6XcBa4Q8ZSon71wNL3fKt1taivDHNWzsoAjBRyCPU72QnaGvowui3MIvJdrVDmgaqkj4QR0yj0ZdZaroTQpWwWM6v11lkhbDeH2XyGn2DjKSbDuj6x3K,Z2q0HTjtQFAx3lLb7Y8bg73Gx6DAwF86YYYOHtdySX8o2tfQyVDcq02PmXO0zzGLMrJoxJ5FvaZgOFVafwiYxqmdO0bIujMlQAFDiy9ZRnlzatbaxDO419b61T4eeazft7KcGqKXar3prDHL5LiBo6CiSkxp9ZY8hR6Htp5fcwr5llwkmb0Pcw6ULn4JRUFFqFhptEDbHMxTyaTKxFoDDk1W7GQfos5v3OO67SachvqjQ0JZ7v0W0epjAetdPE72,6mpClpWf4V2XKXEJPxqJlJeNyjGi8mfZvTgLwlrl2tPUx5khLSSvIKYWc3iu2pUnlRV8Dji7L5EL9TekCzrohBG5KLDZmxRdXpNwVtbg9kK6Zl5TQeaKnRHQVoavjSxANqRQJ7XJ75kYDlQvuE0BsQwLENHzFxfrTbjYUpcKSbGQWc6DMOzvfyhINczr3JnAyKaEiyV5sTPCiTza1ef6D4ckcckpcy3HqtVJ4YPLONSazRC532NrFrq6yDwk0cTW,dLvQhwGREtsY3Clob6KJ6c2nssAqjRQABroh7aV9ZG5Nh7I8mMUZsGsN4OvGgQa3ATWxKNuWXudYkOYeRPCjlZPfWKCjTQdpUTt49amBjbNoe0D0spz0wHPLvaQCb4Z0A8asMlBoYlpOgSrJ9aOSiAgjVurvmCXXuJVLMSV1ivBAJUXZIwsiODJPnZpPHvJzlJqyqum1DR2B35lpHMYMftHnLsLqQ2XJLfHOpnhwxELV9mbiXlJ0u4DjmhPOakoa,BHq89TTcW0RueL59lByFprbPAdNnAo5PgO1HPhg4ATFB8Wxjb9xCr4LKdlmeA39huttY1jeZisWEvfwELSKpOxfnDyCUjNyU0sNO5iiMIjRDyxVgaawWYLkpZDlJ94msPWPlLQParwTHEE4Q95wwBnDdZOZIhx1kybH91IMMLg7ygD2EyctSuXQdyGMDA5k95aktJKsvC50uS5hPkyO1nli1LAcuRnNbRL0NRgaWcd58So3k5ETQLLHa7g4umUSq,kfGin39ZNboV5iXQqD3tgKgRicELPy2wgwSAPbV8XcMUGEYEpS4k3vldK4U5kfd3Z543p7sBBjUApuxXMMPTQy8eWFuFdvNSG6ucSo8iqd7BDtasz3pYEqxYd7wjkZ1BwB0PKFq8XR15hIfA9AifZAQ2VLK0vtfvuAVrNezFkx9Lotk3NV7VxIYaQWFybfzmOE1q6tWxQWneKFM9Kn3Hr4dAmCDtLFtvNtujuYV9M6Asv5b1RrN7QrGQ7vMVBZxc,OYlJH7RSzUX54KPBwOTragqlQjCW5oNwDB9rBDAPC9JMTUgb3UpsZv5yFegbU1AlydOkU6l5CCqNhh1g9aDay2epoQVhsLTyqpVsPfhPDI3s3nvFEnCtgr1kyloivtiCUopyXR4amperAyMBYqIs8HlbaoxwnQ6fnRYxzB5kehYW2TyKmJL20eHwzBNncNs7WG0mJ1vTUfKEtOJICOCwiI4I22Z3fEeEty5P34wblniTZ24BMxYWe63AyxKlZWfg,F9StSQKgh3nK41RKxNTb5ugYPl03AERRoDQt16yTmh10M8WQDb3LNN498UMOQtE10ltJEjlz6ygXGdda7jb5Ptt6WdhygaiX9oRJW0nlOeOxzXk4dLhf8HLjsdhnCaalOameKBt8RRYdZrL5KVLNzfGLEjHKBRfGM5J0JyASwAasNPbWsYzULImOnLEyAhBtO3iyXfYJ7PNQcodhp2URyf1NusuBK1X7gd6ZCaMVhDF3TNxgRlFQOeGosj5GvL5a,PN4DNdQZWz7sZCCW0KsCINHzt0OPNmLH9eENYB2qMs7G4m6uIjoVKhDgPXgVsGcCcszt1dP2GiLF5FWMWlK4hBNMIJ4rg7AIpSjSgITlhzKVpG645FSOLmrCMD5muhhoMSp1ZpFwHztY5FkCoWtn7dMoixWM6uYBt3mHqyvgXuKaa5q8sPkXmFqXDS5udVtXg7MnjcYmVWz4zjIL93FxBttX79PKAiHMc8WiJJz4zSx6oER78w6Hl3Qskqn1gNJA,wqTMjNxDlmt7GeKsfHlFqJpQrzkvMySbSxGzwr7yJI46vnpbJss2W3897Q4jzv4AFsyKFDTlknc3SAFz7VKNepxYLKn37PKleJjVqiwBDiGFUKcXShSHDQTsFANdqnRPh6vXUey3BPxKs4Sr31tTjH80QCax1HGVP6ZiW3XTRKb7ZEyu1JV99wBJoR3bMvOYfd3BARtLrpWsuVeVt6JsteZSalRTNG8w7iIjBub7BGcYuDsAZ69lv6BCPiTakfRw,qe57E8jCOO9s7yqrNPmw6inpGI8tlUCJTXhDqL3lfb6njlfol0N9YN73w9wcnu0pmsVoUh7LUI0Z7xBqJ4gHq0rzJXg5tJBZfU7it4jGmexmRBqPwAvGN0LYPA5vSrWMSC1hRfwrmeBofkFBGQUtWipWFNfwXdXuUPYIJUgq93NbsV0JgaZn9lAbtAi7WyR3cH5exsv9zDJGvtIdYqlhIuDEcZGsf61Gy69alBQK3kuaN6lTpkXVqwmGu5LNWQLD,kVFIZTRx37uaLj1XV40NBFWS4CBqDf5kmuC3qD4Pe8bdWPAUSZwH9YvHM7kOU6Q7vQYaiRasNVl7HsYquEjj7WguKojRTKyNsozsrE3FGvNANtDiCvssU8Nv40tqhkUzGA9EHpMZA1iKy8XHBp7SKCPIj2RCqhPb8rcEyWLMQUNQMb2lOFylNlDwpI59vQF7qUFtH3uxtn7D5xUeAV4Vs6jV9YMZQZeTDRrZcSbEWC8p4WbBXfwBrbjYOtpZAjlF,eJzcZASgIcUQdGQH6k1LAzdMKN89XbAypvd7cbjupbLfbgEmYbgYpXT3HAIyXTvZRGlm7Fgb7nb24ETkc1Db5n6SEZ2zlKgOOnloCVlep5ZeDsnOPDrF5veiA4irqcAd1HPlBnUg4rrecAeOa4rkx5MK1Kt0YObYNEuhJmwREMA1884018M7rhnjcMqyr3jOQ4kLPtPmKzsqGWIebkRnspQym26AmGqFc7nfJjCuoUPRUMuoIUWtmn3Ip5qCsAva,zaASoblnaMUJPSQ6su67gW2S6rAj7oHTXWI47b18THrydI3PGW5EFA4XH4SGiJrGzY57x6PCKjbdjEQMrC0hYY45IDguHL00Rqh4yuHosGYvs1Fwtq1uTHCJlfPJxcdEtZRlLx0d6vT7O2Aex7zaLSvR0npK4pLjEVNE7rupnyCIx4gE0thngVn4YnvThhXRlAUsp6rAd6kG4gBzdopcYsO9u95pvWUvlHbpt2moQ0v4upeB8S1vd4fcXdLjXF3k,29Q6Hx4qPmOk4JG9DITpW0oBTPTC3vSGrOmuwjWCQyxqIKTLDHXQfBmyFrBba6g7CAPQdYntljn3XsTf89WWOCNgvEGygwWlLKNVowvFMtgMb4VpCiyjOkyX3Qv79p8rfTNvxu5vWe6wMtX25FSMoZlC3MrXpJE0xHv5rgeYeXHemwqh38dU75xfSfsQkJEJm2bqaDPJriE5PQG7BxfkoRPsH4vOJP9UtYr9XshuJXbYkkTMEqg5TUqnQg2PTcmr,Id191UHYpEkeB1GUDvOo1YfgrRbcbY8bNFdhHVHqWEquHlqEmj9hTTXfRE6luFcqCsKzetfobAGedFw0No01Rnw9dSxX2CfZaRa7JPueLmB2vIrGxGx3Hx4ppt2mx81sjnJcKOk4ML5aOrvP150fbQY3m9IDLquewtToRIQoDNniSO0hbifQD7BOEa8BwBtuYxwqLyqnUVQa5DwmPrm8lhsfxHGwF0yuXjjF7CE4hF3yf6ChdqGpkf9UxF7ElHxv,37gcbWVY6VqyaKbv2Sgu5m7mRizfJoq0dRRg3KLhGMkZVrebRMCYSHaosLYhlrp3PUMZK8AHgmmGUcZvYNn6ROT0B4FX75LhWBGm93KqDfzE5T1DZUaSgaabg0Z4JYVsrAbLmmXQayv7RIYnk1YOuBYculf0OFdSLue5Jw0cHw24RyjuLVhkPhhU3w7n0dqDW9NrS1AoNI69YxFFvrGYHu0T88cGKZfr3BOY2gp5WW5NsHxYxXTttKVjW84iLJ8e,bUkXZMojkSL5BrSG55PKqEOqpULGqWWeN6Z0jsHhgwjXzkYWsOjGoOEiwbeYQHH22aCjXCfW8yxckUAtigy4rMr2NYGhWUxmfVC0zFT2AXSvd6Jt3f0ax7ZGsUOKzKWHlKI8j4WhlV0THAui4LrDspgVwzQLKyY3FOV7NNEcd3VclJfWlvYtf6rfMHpaLDMBItCJFyFAm6szOQpTgI2XI4fllLnjKjNLa0qjuzxSGUbi2yMlI0mevSO63TI67s4X,Xnwgi1k9mxI8CkiafUtteMwuDqgCwUg56tPyKt6yOBdRTqF0Lq3rFNcQKCNZbDV6y9lsnxFDxtTV8IhEX1dqPjtviieCX0fG885yTwApphkJrNK1ayN9b32y16hzIwzq04vanjtaJtRn11XGcL8ReLbYvcvtCGuLZV7MczE6EbbgFS70qG3RzhWK1bZCQ7NAlg04K5YcQkWlrR1ojGkHw5Gr0U97AJTGYyAeIzOMd9Zx3sLfSqQgbL7Vf7Rfry3O,MUJbcS8qJiNEf5YmoG7GbkDT5WuFQi656MP7SBOkfqFVQugiAqgJM7wDOR8A0JmejQfHaQJg12uAxZszwMtcDgPpBE1uTEuHFHtAu2mcCz8VCduPPun2N2Wis8RnDuUipMmUsVAC3DGOcZbDdKurimD15KxQnRoJpfvOBTv2uatLZK3HDvojPUPv6HkfOLyMgoDfL50m9Etyo1Y7FSfXZMFqxh7mVgcQqhJTrLebQPBfhxfDQ4P0B34oLni5vIvz,ozJBr2YAoYatjINJaM5YRJzMLXuYScEGNnuuvgMsM844KoUgea51XzgjVugIFdTvSpNBDnYlWgjkcTTz3LKkN95sKFTrvzMRlIN5wkdTsAOdip36gyfZutvrjWr9WbzZUoakQrUoV15IQHdurJ4jwy6U3zTzUMk2vHAYMpC2YGaEdb4J3TAma1twnXSLBPUtBNdCyUzPhHt31ouwpZFHwbzchhQOkwK52PUghisaTngRulS8fYY8bx61ke8UvCeH,HSYdu1uOkyORJjSlOR2boycvfRxYuDmYvFfm0wgOsTaLdV2xzr8Z4x5h3LYlImeAjM2g4eCzEpg9ejX1aRX0wfmqFftLTBpZsuGpZh82mbEFPYxSJQzlCP1HyTQQlKhjHUI6PnTQBSSWo7iyXuM6tafkfmsnejHt4nSUW5mneriO9im7I5lhXBCI5w02Td56FVhkeulSNrLxtGW6UqvRFLzX9l9U0K2SLHBRZH52JgvcmidtBEqgdzPWtWSBKnqJ,7Fy4Jy3kzE9NPHOla0RyrSE1yQnsPRe1Fo3K1FT15XTuMhVkW5WlI7fF2sEaW6XnvYMJJM7HHO3RVRt1jfwRjbjpleNdMWyuVS9P6SULeQJZpsPOVPOUavmkl1RaUhT3h0rFh45l8Ff25pksTCvCXQrl6FpVhhGYgZXEzWUBDVbDGqc0FmZsVnQ30TgQqfxBWCPDENRFlV8ej63yDh4Mw6hsnvz9TOrigIg2R5CymMcOftEn4X8m8kC2j1uqkfCS,fm68aKKUpFKAsdShg2vgUC5Cr0XUBVgYiSWAK0JuAmyfN95P6cn8xHhsvdXFPuBTPBwuSEYUVej7BB3ddC5IsVvfwOsGo3TZ8Oxe56vRiVR4GyWFxh31hnWXrIyTDBjTyKrZBIZZYIbaNFcmG4U1IlMxcvsn9orDy99PjxpaoFENdCP5tx6wT4xgqUGBc41iWZhq3oVNPxmtWJJsIYQKcqFiT2htcVUz1hDwtQZy949dHbUphzuLkiKnrgalOcfD,zIzaxJDJiYdLThnW8m5itN63JLTuWbJq91KM5Joid6lQljKKtOUzDj0PtXzG2xSnXyYOEb8AbkyOBRL3mr36rykbSq0NPH3ACfMIGIiRQW92cJSqWrUr5MX4KwFfvlGecsjyxwAxfaxYnAnk6nTMKWz3N3h5fUHHcmmqAiSawU9CsniN4olGgBYz7cBBAYCdOTWVFMkvIpJhQmlxYesxEK5w8yUcIgp4duiLEYBmbAhb34TzOpORCvkYLSAp0XEI,flg66vG3YOeS7SdYPjg37E6uIYlCSmSCGH9gorXyWGoslXOZJhiDakELSPvbr5eZQa9v6fwMZCnZCtDNkAxcC0IoSSQH7E74SH67Nr4Qtvw8wMgZDyfrxq2cgZthSWpItEfswAUnTog6HF8PrtkFZ58AWXXGXMv2uuiwbNk7nO8ayWXWs8kv9AFAGYnLLm38enNdlfILiupyRDtojy1KqWjeNndeqKz4YR0l2CllvmmJhr2pWrJqQQBkKNIMPHBj,0qN8UypPLSIKUl2TJZp7mFsPL2sSuFfsJoIZL8l9QL7EwQkr0AGx2zByF7dQ3widO9gtPK5f7zMHGZtcfMy0n4BY3UvRrqKYnnTxmiJeii17AGXJMVxAN2SdOpyhugS0KpHPZtG9AtGPJrzJOe9sN3LKmpwyo72NqzcIHU1tOAt7NyhxZGXB7W3KMNPcRHeUnvXh8YwCjWsVPMN6VPWVhTvObdIfS0p9OIjhtX8nERduuEdLnP9R5LXnQI3AIWlz,VM2e13Vtt78DpYfm5XzYr8t0ad2HC8RHBtifoOw4ZmUy5Cb3RBGfqYjkVL5cn2M1mWK0M9IuLDeusTk14vHuzCisVTIAgwFSE03NCS5r6u7lbjNQZnuRNuH0G9iedLDlr2kdSHVLYAXrkjvlJwfCmZWnYljwJvsWkBBViBXEjymkVMjfRPOyCRx5Xt6hgxJstSXE5ZXiz7wxDq1O9lLADui1asKQm9BpRoBWSk4IdjsStJmrpJOXpS2NoW9cc6H4,N4f6D3aj787GWyFE9KwT17jzrxA8Z5eTQROgJ0rRwEZYUwYNYL1ZAgZL8QgUajRaduZGuJilCvhcE3581zUoXczAoQkaH5SwSqkfdRAoytBXIL9fOfAkOUHOLydsgHHfmjGNyZ7gqJiWJR49XwNIIZGWH3lTBhAZ4F11BQd4dWDku6NlXKokbRwTWO5eqnbkDekpMXGde3QyMTzRpVpvvpYXHLBR4VputiPQRH0TnJXHsfA8SN0VfG9VWHbes7l1,rpYy4CdJpkVaToIiyEOx7WUoRr1sCxts8YI7WZlAETqi95qHB3kkHKrZCzipV1J988cah0PZBr5l1KAhpq3jj9sEtqJweHKADwvF746CzRseYUPZ6J1tochNtzVmw4G8mcnNsBZ8zLfOJNCSYpeuahGhodlOdALUMHNyK5hqYG7s1h0UxKhQjNVA5rxijnR6jpPRxFBrJbRSOcMbJLjZtPziTUpdiPFOKlhBHA0BsuxAwifPcWH9B9v94rI6KGPj,dKhAX7NAx9cBAgZe4pKZAskJ2EXu9WNZDdEqrKz7oZ7hQU5IN9vod1n0QcntfXD8g7IrEAntBlvqRtzKoRMNoTobnJCg6I8fN2px35YUWKnyTV0KL9OCEMKktmU2Kqa0c0HzuPOctJ2RIaTb2B39Jc3PGAIOxqvPDHa8GeNNahjzi3J1BKfPrppO6SmIyCDY0Vh1N0eiBofpnV3u5e3wc3Gg6D6WvROUlTLJCBxlh4H7cQDBd4Gwf73NRKEB74II,I48Bcj8ONmjMeecXknf7Wy4DPb6VMvfcTgCB18ukQtb38Fxm9EXAd3tGb5JdzIdYxuLhq5JJPmLlDifVaHkwMJ2XlNBb5ahfnYuhrrN0y6H1J5TVsiMiCkttsLNa3cSEHEIs0zPUKuYaAo56M1guGF45AuWhpkEJnB7KXe0eBHQRs6IjoHA9Y2DXqmQXMvZJMvSpIwdZtUYihbOCT8fxtSKbyNY0pFTDIELI4hKG5HHOQLjsJnSwM5yRnbcwsx2g,Vs7cyyFQiVhh4vyOhxrOcxIrDC6nBVo8LzEcsaPKf5z0ua68as1cvq6xyPtvwPG7SQ7aOMpgRH2s2GXWrGTgKLqGcPGroMBSaydunz68b2oyLBAkAwdyfgLhHyNZux0M6hXeu6Nwbi7Kq8DxIsIuXmd1dUqYLXWETeNw4urvQQCowB28CLbGJlypKdmeeCL8RFVHEPsuZQLKdRD5LHHt7Wz70n2qhCtxAFyrMwidAPmRYwu8qj15SPsqmyYdzMq8,sZR5OYySBz36TJJgJ33R0Dz4m7YhizJBeAXB4f7WmJZTMmxWBj31tMJdeVsRrJATezWt3GZioydB1S2Wj1hSWfnwBpt2OXOTTAjYvdGzC7bFiqqD0NI0hGnmb0TiMATUgv84hs6tGgo4Dxg4rw1aUbwWg8scb7haaElDm1fxgHpbaOhB4JWiQhBSmWHPono8aJEasFf4aRPEhKFpxf4jjlGHN72yV2rhIfOA19wpoCVc6rbmBtt2DXifIht9gWY7,5qYoUvcqJEyrcoeLjgxB3XMOkriYcRSZ2MXI9mSanU70hgFTZhQ5kOFP30RbzkccT2ZkADJ6p2bCvQa6bvbBHLnSUIVWcyoc7C7MviEgxRkpnLiYgDArZ6Ev1pjKVoEGT3kxtvPWEvnnFd0pPZwNmFVmhpzDxvESUMhn6o23P3DpLLI30hOKyFDklrjUV2UKEaW7WSewFCUAHfIqipFkrqHNRTUcvP9jT4Obn6GoC8eHlACIDfYZuawSgQ5VPo3J,cvng6DEORD6I4kXzF0wrBa0Plt2ham2UrVEHIU5NKB6lax2i5CkBJzrHnsf0Em1ISFN6imXp0msVncCgGuTh4qaSXTHcxFdtTu2Wy7vTTStTFR41A9Lq4SYsPlMLWRLNWSSLEmfcl5pfiuY9ET59oFC3OYpnpZbefVtHrO50v3YLrVQO1Lukuulkfwua2uWFUxzn4vRMT2cbIqGRQ72rWeM0yTva4MtzDxqpBxEw5jtvX1CsLIeJ0WLDyBXinlZf,URrUfzVmy5bqfMLfx7h2I0an0mWZZTt2nkzzjOa0qq05orV48OBbcTSHd5PZHZoCJKZD3Dtd5uf3tZHsC85oyKZH4vv9dtakBJ0OmRIcBHbjKYlyfKsj26KffQnwTINeQsNGEnrXgPrdxZ8Hky8UCdyf7OSY51Cqjq4hpzDsirUq9LWvOHo8daMdAPsUT12hnpAfZmzoys1BpPO1WXbanmUgJse5Ugt9kRYRGPz5YEjRcfvrb1jWQ7VpQSJqtnxg,slvthRWzqePbOJeotfSbceLIHehrHPziGwvQiFvriDuQH07dCGVgEswrmbcYfYt0p86OzZeD7M751i56RqpQFsMpjkQxwGRHsZyKi6IXnlMzE6SuNDViBnrc8eoVmO75t2KbmNC5HOWOp6DWUWZCWibjdWXCZEuiz2odMMRgepIfwBGFWaAv2aCgFaDsg9PprnydK8y1RyG81dIFtQpCyngpGGiLYLqo1fAAsxIxYnsiKrK9LGIeP2JRl3LOzPSj,7pbTuBlgvE2JiFRfxHFyEn8tedjECMwVx1oIXuJMzlck2U7RVq4xSUaW6IM1sESCXQL3ssnsVwno2QClIuq1p9dJ12ui32fMXVTGOcDr6dJH4StCpjf2aLTiQUBXZrWYeM0onzunQN3u6nO8Tfb2Q7vOkAHyEvymhSCbawcCc2R6xP5yqSpxkO0cMcBbQwmKxW66yOTiZ8Ju7bFpkwcgn3G0GFevFOJHNX2rm2vgaA5ZTH30b5gx0nNCQaWNfd8I,RSi9BuUKNs90oNGagAnXg9sOxMICeGLZGiAElsx5ZciBJBXwljagkGDWlA3VBAoyqnFjnzgqWXflNkeek0sVMLVItEV1dHBJ0a2n7zMwOwxSpPiMIpVcei6Pk7xJyRKgYKzz9GZCF7eGUiSKKXVhSmllc2LvDqAdC6dupF6HfiblBcHOebTUesqtEnHJAyu7aRrEKCbvNdE9idmNlzakfediCU1FhY6atIPa6cP86dos3WTOmgMiAr8dKqTK1T7zRlRRdr6n23oRzAqALtORyK7kJXVdFvhgcVv45VsIrwuiJprP0fYRzSVnsKOPtkScWrQ3aDfssUr2W78RbMYTuTcAsTidliJopB4VjjixDeGaQwMOJLkUt7gTY0l7sWySVMIw0mPiGh7GA9S2rFi9sLf6MzeMUoZlCXZq5NnXg5ocd9r16PXdutTRDYos3qyIHQWfXYX0E6LixofhM2fNJ26eAbc26JTTMeKqteaW9RzGOo2zGpmE4rHABmuoZJN7ZkeH2Z8rbBpGxy4RUJSb0TrtTATFfTqhs4EyKtDjjIP8B842pkli3OztqgHCPhxYckOgxCzUI2KTHRbcgWTrTmtTbgjSAbEN4YYlynlSF3oVhC8AVUY5nEfZOE9ElELcyv47mXOxNvD4TmJQKUWLM18m6c0Pnfcj1SN2D8qtep25gzj46OhkRwtmCJRQ17ATD9QPaWtZ0VsRz9tgeK8r8t99qgVW9HxkvPy7lat6xrbBslSQ4LD3XMZQ9v6QHVkM,smHB4z8XBfhDxG3O9XVlmGumNgWGImPHJ9Vl6avl0GHVMF6tOZYSLks550CaTMxjNBAswY7emrcwuuw5A8HUpU68hxGASJUwYVd8r9ppMt1tmTwjnScXJcUJc27En5BU4DxQeOLoEaxtEOsgQzhhQMtnZ6kyArCLBsDpWP6ofKoxSjyok8d070Z2DGmzy6ODIkrUSz7YX5yDYsPSKq3xuJ6aTNnm8jfADF59rjjRJhPfo0T6bVl7cI5nvgXqNt4P,N1kNs38OrI68bz71e2t9XVgRYtZr8okZOdwYjD2kF7Be0FRwgWSY4VXSCmibv81LAWIfKzhVtbaaYdCifD5d3dLJipovaieF4kqIlclDd8JMCZL6KO4GbiXiQTgh645vQ9K8vs4Otz8MCTK69z16tMQ9rqYC79T4fji5zWMQdz07w7d0v0FeFA9jAt8YQK0kqtijieQFAYFhN1jaRZjYUGgYPXS2ejwVEzzakt3Pr5v4sdl5cnm9NzAwrzEnoedq,XNp8QqoXFIHFxhoRc9ZpcjokEtInotb4m06wgV9C061SwpAe516U0IuAO9v229eVGCh2BEqxoWeLxz4jCSyb1vnd7ZoDMtAgcKQtSxplnT1PkssJpwBvIcQ4qmyUFKZSVL5QDA2L2ZhGB2ufZG7pqAhfbOlCsZI2QMnxidgQbvGsLpaWI0Lmcrtd7JVUS16NuZJDG6uNhxRmHgTy1HxkIPGJ03MIgYUgl9KI3lH1UOYGoUR1U1avNWNym8qQewXl,Zq0CYqjuTaOrryKEdK4dNplqSIfGmUl2NEhfexXgI28zrxRVlqLFPc37l9JdhomRs1LYDuM1QPVV4xk7QV8isqYa0UtkogZKAeMzFYBgD02ZzLyMSAXM9ne1s0CxaLV7JbHBNi1Knk5fqWA6fDaI6f0AmrwsvP7GgqYIBNSBW6VkZGuI12p3BNkQ8ewrUGd75Ohndl4PBGcrmLNwTBFydO9SKSAO2K0fZPJDgzyYRs0l0XwACA3isST69CAUcfxw,NUldf1RV7LR9b1Q79zQWwVbl99SMzeh7ZeMo2EvXpRGN1ZtQuKnEdfcRCw92rBKTLAdB1aqB8leSKtFH3CSLEGGqv3MSh28z4rupIdgRxIjC3eLNrgj9JBD8y90Cum7GWz61n62QOB9DkREz4OTmx9r6ohWZOh8ifFZqta7KbFHsSR5W8A1qCp4cUi76rvwH1mnlfHgkGyhUkTld2KgGb94MwslnRWb4x63dT4Lwz03c2VaEdTKNuhjuPDNmgOr7,jI2PwWFA0PcBoRXNUhCr0NvMesEoM0JKpbYORLOTR39cyvvUQo23SEn1QSn78jYAg5aQgdOI4tYTDGPzC3Kf4Xd8BqId2Y47EqvKHcUOGNW58LJgwHXJvBiDTLvIo8DWFeAmHnJEFfDcQv4GxkdzNTzf6vqaJP9555G0OAJNYyLTh0HHvt5ktjT038vZlaK455OfYzfl7rf8cDtrAsIs4s7pNgrpbmv3ISGAvHrisE4Y508szKfq9AleB3nfpeyk,dEs1RW0nIZkztUOh2PAbSeW3YYFuw7xlcPsJqTp2XmDgZ7O8wxzZU3H5yCNzYFMwZ8KDyz27MpKEN8w43zRuPbx95S9TXX1Cp0ZN0jqELdeNE2fJirPL9dduI09WQ5pjfQ9NPnM7ClRV9CgYmtC93QcvKuai2OVaW5vghGjigjWacwlVEiXzm3oQ5UxSlTL8p5PzOjYntSwfq3Qxq4hGP0e4XYd0ZzlhVKuIxIMeB9pORhIKZwEHSXJBT2Ka9ZNhLGT6ZfSyXmqX58HmuPvpMgtZ4yOjisMENVmONofc9DFSgvuAA5qlSvfwIFi4Lg8uJqGpxDvnunCzvxLJyJckkus5jqhATPN6HYkwwl5Wlql4sjZhvjcbhlBQ1dIlBEughGkMQizi1Ln0WbNEmxeqXsBRHLTV656HfVTJy6a41qODFTO3d9Pz69XtQbqzY0RBvXAqIiM7r6ufaYSBdzWGgsxn9u9BNc7kKR06KmaAwgjjmzdg95LYQRheSjUgK0TsJOUnOMxSdWqttrzIRs070EPjhyQeX1TRKF4mxQquoUzr6Jf7qp7IrcB5MjpbQP9yOoDwW9PEpmMkYOoOlXxjND0uVJfYZKrf22Ltyf3XskX0pW8CmuJUY0jJBRrCnkIb2hhMRycgYRgtkT6QhfPagijf710c7aIEeoXAwzKH2TElGtrhoEBSJ6bMziPvx13Zlyb1TJq3xJ5LUjLRiXedKDYujN8pOE3fSNQS3WXeDjYw0GEPLDqPiyPmGelibS4j,KTJQxTyYgjGNV421iksjO8CAkZQQyADQgffXyrDLq6cDpol2L03QrwuU654iurp8E84E2Fh4rWdxLf6geT2XtcGAFJ6nphDulkbsrRksRxec8QUs79F2XnEMkES8T6JWqkoEzktcl81iOqSChw20KnW7J9K4oSJtHX9C5VAzeKWGqBGmZ2MQAED9cQ2xMFPuYKcFPYjF5wR8r1iEIhthaV5NF499oRmtfno4de3foullf201SHGfYaCXObOSw721,tR20hj77HdrMVCktKyVYpuFtBnGWWZ26vqu30e8oYp1awfYFlqwlgBTSTzcb39UWTqJ8yBegSYJjWrHGSAV5zKYBVubWB4WMGpqyUZubtRCPyw6kEy2hg66J7I4xfw5KGQqm7RllCpbM5dbrptl6dHWqGUsENrNhEzlOggDAYxbhcuJlTlMvTriWT7q2Yn4yb0IPRnimrA9DftoZH08lPbVVISryHOf4FRZndi3oDJQz5Fwk5fXcN9HbHRh1XpV1,H0p5muig1qCTwirjQOCAQ9BWl1SPiuFavF1SGjDBq9Wjxy7jAydqOK9bTYsn2FUHWnQkevmvVXa9QlvvpBFFYeO6lHA8xAIdVbW1Bbiq2mDiRaWOmeazPByVmRqQjLqpftuJ5cBB71J0MZcx18Ky5bYf2wPt7ofJtjTCYhhN5qbGAGAspr7TToAE9G6Fsj1RxjcXptPhhiFNDkVlq8PUNWhAWJZ1imH7HDddgEZJOhzWdIFnGFhslVLRXpKx0194,79tDeoQYTtQ1QSiXuFhRWiU5Evg7sY0pZWWLWYu1VDosQCwGMeNjoKY5HsaGRHGNEYOCnmqMwuWJuhAqgYWsmA5LnA4vlMcO6SIaTL27bWiFmm3BqrtMUDiQw1tGia1OSE59aRzeGfiGaSftJEZi2Er8Zq9RSiKrINN3zMjJNnmAM4beASGcglfEJFMU4691SWLGRqLKQe3clAgjR6lQAJiXyQD2UIGKHYUcGMm3ctVsdfsLRutIvA0NqDF9Mzba,IFzc7CWEDoLuZJI1ezrzlu5Q0kKSWx46T0npEbVuPeaVzsyUQFGDdjZdJkhQeB9QE0zvuAQUbmT77jGED6t9VFSvynThJgDJ8KNAUFULEskWOMJVn8QK4GYMUjgzvVbffWWGBtFOz51OUouOe8F71rnzlNy5on2UbwflbtVPJAl2rTC5AZDtIjbUpg1JQO6QKEXBCC2Bo54TpNHizi54axYiaXy0P1CPmQR7h1Y3cq73ELUhYGeenHWMi6HKwVOO,ujM26er1SYB7dg3RSuHmIEHcVVEAUq3TN1QXUz2VaglaPGBDw4faWI8HgWi72Fx0o9bMkbGnh2hkEdlteLHvr3RHEJty4OfxYzIVRlBjZDT7uuyZ9b1qJ6uD900Gu4mDnoPT4cPp4LkP57krKGXeOHCKhTosOxnGeA8QkFKMBTocaYdn9xEXo9vHWHgFeHVX9MlrgwfVFoSNoOZFWpLXMRV5Yp1IXHdx90RBxFeIJP8D9vxaluESjl0KJHkh1gxv,mDTCOa07CcG61sryFlRavKzkN09weg1p2l5XuNVB53eaR6a1nzg5H81V8SZZuBCfDhvIIZCZsUN7lVSYcyi7hdNsO3U6xhhlOnvcJQmQPlQpCrDvDcNCNtA9xZ5LUKPTYeo74xoaoZL5mTSDp6jOxN35Txjetz9kIEYLIqnEIi9LMN76JMxEhO0M1ArRX5xFNRYfBlhqMarbMAgpGHqPdglkOlShcwli4TanK5ebwPVRSyk0Oo1e8NLqH8P7aIGv,uzl1umbaOtcAK0cVWM1KUwFkITBEmZLogg4aZnmuyb7xwnqzyiJViblNWNlB5rgxg3FM9PBH4Q6Rba1UCrUS3yzYTed7ncf6Fn9b1g6EMHhfrKNVN6F0Fov7CXcZ11RG2fmx1TEjFlAMxrpBHZdhhFXEhedrTgfc5OxhawyjsZ3FS4klcKy6z055ptD2mvYVLvo6hE3igrBBlt4tqbQNsME7sYtuVjLuSt5qeStWQup9Hdl0OBirf18QN4wvn0Pp,zvSdDNavue8Z4NlUYvup2hnCY8WL5cLTRTEwG0PLBbTdCPlIn5lJ55NxTyclkLolJ4pcnY2ZA3Q1aibk21rHM9OKp0kCuhveDPMdxbdxxxWmlDcVSZGOaIA2QzdtKesp61KU4njY7BavyzWiNfbQYRfcgd5sVNmughLL9vmKMIOmAsrfjTCd5Khpm1FXWPIq8tBQHaCQFHK4x4j9k42cMIxkdRl0OQGSCPzLI0at7ZE7YzZT8wLY037RlsTnTSNu,FqgdgvK6FXZYTV8lQau5CmK1Pmdc3HIQQ3uTBIDpWzo8OyiPy31eBvAAREecesPA3lGVCYo27yTcxwjPGVTZio5GMXicoRZFmL9S1pRjz71nmjEZBXrRzwbYek6vULLt0dy0LsSeiE6ZsxL5v3cVApIscvIMV5UP73tSDWInZGRh3ttr2yAiwUspU5EIkEGyyzKj1wlbeUAmDyMrJubSTqA710Z71k6VAlPozME0TAkkDySyhq8cZe30cVjDezPC,53MgptgC5CBXi8Oe9UdxrHo7ZKzHfutYp8p8qgxibplWY18WGFun3k28jRcxLOxgE0DTqrZCjTlAwk'
2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:,9
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:9
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:9
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received all data: KZR1otmya0dTYQaFFu5nEj11dBndC8UUwg2ccTZEREV5XAQ7NWlpKrmtevmDGNNPerozPzErwwcIiOgTb23AYzOGaFvK0xBdn4uM1A6skBrdnr6GIrdNzT0gCaD0OmI7WkRedQo67x0TvaIy3JkPBFQVMsBCtRcVGYbS7xgl4MTNdkesxk,0PCf6Lbjnx8AUWBI3aI9xJSa4Me7OwLfdB31vtSjBFXxgXp9fQZJ7FQ7PtX78LWfGgCXJUpfHiTwBtTnG0UJs5gUGcYbNPfvdo1TShSk7BBhyo0bSWCzon9GasHpn1r56ZBBdMal4o17YUImQPVC0sDJBgnd942aF82FnQGVgvhLxnH7Ye51W0NXVqVAUcoILPy0dYnHlPm6YMVQlx1ax8s9wWQfivGAI1mQuQPtaZsXUI3DCh4IxwmHA4sr3CXL,YfysPDcvgxf00QjRlCeGW6iXKULVnHll9wO2TIZ3lsZJkGKjqRkGYVZotnoPm8KTwl5Uf6tVOCw5l426YEMP74AWWeesjZDAPCK1T0Ccpy1nhhA7o6Ibhm61gU4SKUpK5zsx5iax9rOZOldDlzWGbqYkAfyi9LyMYaa2lK0ON4eWPBW99l7Oi0XwcydQhcUQoxx0YNQuGUUjqolchS3ivm8F8dLuOoVKroJHZtKBscoQifjvWc3dqjQitW5ToX7C,EYKQNWCDZ9NqGwzF272rriFYEdDAJ5rU65OiJmRcLjkyJRNxS8x2jbYKXjN3J1rnSsJCVa6zjU0STqdHu9smIJMV5Zy7GsMU9JAVL4eZs3slxsehHcMdrQIsNtcVznngYrvyniVfPhKR7IgwM2BjGFaVPYwNda99YEhDOvtQZOxqykEiqtBKk4F4z3xvfADbdXDASY3dUzx0kUGtkbH3Qu22hxJkZvlEti93iWoNekK2iRg7XMeNV8e40qJ49D5P,jtTgsFphTEG9Yw8o4qfamNpNiRCr1Zuyh4J2ZuWdvslZ80sDphwx8Mi3GtK5n6YKE3vDs1I5QD9Bgb9DUmPT7YXOtIsiPgYyBee3RShpnAOchGtebNE6iYkWBeNRmb6ZA6b6NIitwV6dP7BBqDIDlEqzCfRWqCd2iTqnDsoCCCEzk71deteTuPfKuwIO4BbhLFTOTzjk6G95NfODCGiwy7xxWkymlCXUpAdahJcOhE53SvsZZlhGtKBa42s3c9SQ,mt6o1wrlRlNaUrfnBpsLVaioi6oWrn7RcIBj58pID7k8lMTKHAepRWfq8cbthNIYGcK1IgDojydI3ralKJqONdjXehuxvt3fm70H18ushIXdU7fbf4xQOZLFXtP6bbKDo8jEukW1eEIbwxMdJfU8vBCdnAZpxrqFBbFcsyZ391AzY0MaLZVGs7tK7B9tg0JW2EhCyshJpP7EUdWDStVIhkkLm5TF2jJMACOu6sZ2e3OIdaOOeluHZtn2mJzw6eGs,3iygIbv7DEjEP8qoTGtLOv3vZAWjwVbwypAzurjWhGjO2NninqLGHqGbJA2KT3IiqbI6kynZiy6NOmvN6GDIk2adc9YA33osSOBkLbVxE7HzXAjNHkY1rXRcqpYrY7zU7xqZz6jwwRoja0vghowLXcqfxjbzbWFhKFS8LHpZDEesLUVitsVTLxzoXQTY3zVsbL37uFQnUaICeJJkjX139tA2kpIUCrsFPncwaV6vIr6UJJ5RWwnJ9HVtDL6ASAxU,wTYhljHvYeEFYP5Foe5PpEbB6cVMe3L3mCSLAWapywHJy0J8jL4JsDphjoRRWR2eTulbdW6kwDldi3GsLNE0uOe9pt2in6j7Qw41t2G7rOy7qodM66RBOo9dMbILM6CohkBu25VdHS2s49v1GyRqAwhy7W0pUSdgwmegmTJwdQsC5JyCNet82h7iKTZAyZRUlPIGqIEyf1vxlcsFBsEcplPjgxMMcDrxi7Tqqb6l8d94i254nTaV7h7xvKcZ43K,A,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,4,7LXTb5EFbEFTh9rsx5ChkuFkkDj9BuUja9CqUuXEmvm6a8qdNQikliHZPOPHaSV2ZQjhok1jG13BpI9ZsHN7ncvYuV3iUwYDliILaaWbibWfmtX25vihELYLCni5xhyJBhLTeTbe6GPswPFz8hoXyK4ZQZZC293BvGX9RTXTwryZ5iATRVVALqAc19lvlfv7mIXlmMfEftL17ubMWhNl2uTjRwQp1GlQ3npJEJJjyLgBl1Ns9MoFMdgl9U6dfxUtedZgeqA74LR9Uo5GH4LJoZ0F3r2bbTp5Gc7fRuJhsbXS72YWa5PAdHvQBSU9ENuwRyNTOqOiIcEPfds4CHk6pGyNAJZrhLPbzKaMTb8JmTU9v9dDlkc2kVMzjmvUlJm4Ow20aQwUpfmZLGbbRPKjKEfEPSv1RJ49wbCtdZcQpGHooc8uxul22twUFbAXpYscNfEXKX9domf64AVADF0wMlgIDlS4zuw0gwGEnhyVpoU8fV186st2EmAr50oqJkG9,XQ5skQ6nQVb3m31Ql9tWRoUZMccQnwwBCMNKobAcyYwXSUKG98V8Emygo0OiPD8f7meYHsaczN79J1lndkZcf5DHZb7EzjeO4tvPIiqXkZx0RYPCt8PU0GiFeiAnVXjhmC9ouLWNmoDX9FZhFcaGY6gE9Vbmw05tvTQ7KzTTQCNGHoXMGUfvvfpRVVvIWz6KhKhu7kUHSxKNl04GZq8kd1rPDjIJYFwzn4RV6lOtgpDCkLQEkM76EyBTqv379wiK,CST6q7O9Q4JPU50yRkAzOitarh17TmQTPOpty4utHs431IrpDBEUt3a7sx2LngBugdK0P8xLC149PK4GZiIWF4GoBOkTVQ1zV0x5vnCQM037lShUVxgAIgfXvH9ebm4HlCfcfFordEQ1GrTKc2h7Q62XkM0zSRTitsY5s0kQXzDKTG7cr3yaaE5oXBUOuOwrjAH6kKj1AGdgLWie4ONEnhGhhjBvhIpke9pY0MnoELhz36Zj9iZIvo7W8rIFRn6t,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:9
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [1, 10, 11]
,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'
2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:10
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:10
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:10
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-10-12 14:10:08 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:11
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:11
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:11
[ThaliCo,re] VirtualSocket.readDataFromInputStream() read: 0 vsID:10
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [1, 11]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:11
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-12 14:10:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:10:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50581
,[ThaliCore] Session.disconnect() peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1
,[ThaliCore] Session.deinit peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:10:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:10:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D956AAC9-65A0-4008-8432-20DB2403AA45
[ThaliCore] Browser.startListening
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D5CF258-9502-47E8-8BC3-9388881E8557","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BBF9DB54-27C0-4C93,-909E-CE62E7FD08F3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4D5CF258-9502-47E8-8BC3-9388881E8557 (syncValue: FpzFx0U47FE5bopROneKkCqIJtWWUy40)'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BBF9DB54-27C0-4C93-909E-CE62E7FD08F3","generation":0}'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"67A7E480-106F-41FD-ADAD-2706A37CB77E","generation":0}'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:4D5CF258-9502-47E8-8BC3-9388881E8557 error: max retries exceeded
,2017-10-12 14:10:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FpzFx0U47FE5bopROneKkCqIJtWWUy40","error":"Connection could not be established","portNumber":null}'
2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FpzFx0U47FE5bopROneKkCqIJtWWUy40', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:10:21 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE (syncValue: K4AQgG6JwFn09hle5pD6ky010WVKYCYA)'
,2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50606
,2017-10-12 14:10:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"K4AQgG6JwFn09hle5pD6ky010WVKYCYA","error":null,"portNumber":50606}'
2017-10-12 14:10:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'K4AQgG6JwFn09hle5pD6ky010WVKYCYA', error: 'null', listeningPort: '50606''
,Connecting to the localhost:50606
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 11, 12]
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:12
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:12
,[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:12
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 75 vsID:12
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:177 count:1 vsID:12
,[ThaliCore] VirtualSocket.writePendingData() to write:177 written:177 count:0 vsID:12
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:12
,Connected to the localhost:50606
,2017-10-12 14:10:27 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:69 count:1 vsID:12
,[ThaliCore] VirtualSocket.writePendingData() to write:69 written:69 count:0 vsID:12
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:12
,2017-10-12 14:10:27 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 69 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 53 vsID:12
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 11]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
,2017-10-12 14:10:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 ,14:10:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-12 14:10:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DDC5D80E-EA98-4BE1-BC6C-F,FDB05E03CD3
2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:10:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50606
[ThaliCore] Session.disconnect() p,eer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
,[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:10:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3F732965-3C77-46D7-A946-F17E3B7CC083", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3F732965-3C77-46D7-A946-F17E3B7CC083
,2017-10-12 14:10:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:10:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:10:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:03CB93C5-E494-4904-B899-97A742B84DC9
[ThaliCore] Browser.startListening
,2017-10-12 14:10:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:10:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:10:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
2017-10-12 14:10:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"67A7E480-106F-41FD-ADAD-2706A37CB77E","generation":0}'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 67A7E480-106F-41FD-ADAD-2706A37CB77E, (syncValue: 0aMkFQUI6fJ6p2hUrTZinOplohzyq3DJ)'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37,CB77E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
,2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE","generation":0}'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95033898-78DB-4672-A53C-705177BC68F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
2017-10-12 14:10:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"95033898-78DB-4672-A53C-705177BC68F9","generation":0}'
,2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F732965-3C77-46D7-A946-F17E3B7CC083:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F732965-3C77-46D7-A946-F17E3B7CC083", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0)
2017-10-12 14:10:35 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC","generation":0}'
2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:35 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:67,A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,7A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:67,A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,7A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:67,A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,7A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:67,A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:67A7E480,-106F-41FD-ADAD-2706A37CB77E error: max retries exceeded
2017-10-12 14:10:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0aMkFQUI6fJ6p2hUrTZinOplohzyq3DJ","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0aMkFQUI6fJ6p2hUrTZinOplohzyq3DJ', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:10:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 95033898-78DB-4672-A53C-705177BC68F9 (syncValue: fyzriMQ,qAzUE0j8UXql2HlezXQ88yhct)'
2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95033898-78DB,-4672-A53C-705177BC68F9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:95033898-78DB-4672-A53C-705177BC68F9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:95033898-78DB-4672-A53C-705177BC68F9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:95033898-78DB-4672-A53C-705177BC68F9:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50622
,2017-10-12 14:10:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fyzriMQqAzUE0j8UXql2HlezXQ88yhct","error":null,"portNumber":50622}'
2017-10-12 14:10:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fyzriMQqAzUE0j8UXql2HlezXQ88yhct', error: 'null', listeningPort: '50622''
,Connecting to the localhost:50622
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:95033898-78DB-4672-A53C-705177BC68F9:0
,Connected to the localhost:50622
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:95033898-78DB-4672-A53C-705177BC68F9:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 11, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:13
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:65536 count:1 vsID:13
,[ThaliCore] VirtualSocket.writePendingData() to write:65536 written:65536 count:0 vsID:13
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 102 got the same data ,back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [1, 11]
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AE75EEA6-D468-4610-9059-86061F105BF2
[ThaliCore] Advertiser: session connected Peer(uuid: "3F732965-3C77-46D7-A946-F17E3B7CC083", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AE75EEA6-D468-4610-9059-86061F105BF2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AE75EEA6-D468-4610-9059-86061F105BF2
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE75EEA6-D468-4610-9059-86061F105BF2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AE75EEA6-D468-4610-9059-86061F105BF2
[ThaliCore] Session.startOutputStream(with:) peer:AE75EEA6-D468-4610-9059-86061F105BF2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [1, 11, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,2017-10-12 14:10:58 - DEBUG testThaliMobileNative: 'Server received (12288 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
2017-10-12 14:10:58 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,2017-10-12 14:10:58 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:14
,2017-10-12 14:10:58 - DEBUG testThaliMobileNative: 'Server received (12288 bytes):'
,2017-10-12 14:10:58 - DEBUG testThaliMobileNative: 'Server received (8192 bytes):'
,2017-10-12 14:10:58 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-12 14:10:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:65536 count:1 vsID:,14
[ThaliCore] VirtualSocket.writePendingData() to write:65536 written:65536 count:0 vsID:14
2017-10-12 14:10:58 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:14
[ThaliCo,re] VirtualSocket.readDataFromInputStream() read: 0 vsID:14
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler discon,necting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [1, 11]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wit,hError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-12 14:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:10:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:10:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:3F732965-3C77-46D7-A946-F17E3B7CC083
2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14,:,[ThaliCore] Session.session(_:peer:didChange:) peer:AE75EEA6-D468-4610-9059-86061F105BF2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3F732965-3C77-46D7-A946-F17E3B7CC083", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AE75EEA6-D468-4610-9059-86061F105BF2
,10:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:95033898-78DB-4672-A53C-705177BC68F9
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50622
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:95033898-78DB-4672-A53C-705177BC68F9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:95033898-78DB-4672-A53C-705177BC68F9:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:10:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fyzriMQqAzUE0j8UXql2HlezXQ88yhct","error":"Session disconnected","portNumber":null}'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:95033898-78DB-4672-A53C-705177BC68F9:0
,[ThaliCore] BrowserRelay.deinit
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:287DC006-0F86-4437-911D-696EB691D295
,[ThaliCore] Browser.startListening
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:10:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:10:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "248F322F-C94D-4AF2-82E0-F19CBC6314FE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:248F322F-C94D-4AF2-82E0-F19CBC6314FE
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:11:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 104 We should start updating fine
,# teardown
,[ThaliCore] Session.deinit peer:AE75EEA6-D468-4610-9059-86061F105BF2
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95033898-78DB-4672-A53C-705177BC68F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0)
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95033898-78DB-4672-A53C-705177BC68F9","generation":0}]'
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95033898-78DB-4672-A53C-705177BC68F9","generation":0}'
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC","generation":0}]'
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC","generation":0}'
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:248F322F-C94D-4AF2-82E0-F19CBC6314FE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "248F322F-C94D-4AF2-82E0-F19CBC6314FE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4B3D5F4B-8FCB-4D9A-B208-1C8BB00DA397:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4B3D5F4B-8FCB-4D9A-B208-1C8BB00DA397", generation: 0)
2017-10-12 14:11:01 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4B3D5F4B-8FCB-4D9A-B208-1C8BB00DA397","generation":0}]'
2017-10-12 14:11:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4B3D5F4B-8FCB-4D9A-B208-1C8BB00DA397","generation":0}'
2017-10-12 14:11:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:95033898-78DB-4672-A53C-705177BC68F9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
2017-10-12 14:11:02 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"95033898-78DB-4672-A53C-705177BC68F9","generation":0}]'
2017-10-12 14:11:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"95033898-78DB-4672-A53C-705177BC68F9","generation":0}'
2017-10-12 14:11:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:248F322F-C94D-4AF2-82E0-F19CBC6314FE
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native',
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-10-12 14:11:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7C5D6F30-ACDB-4898-A9F1-21CF7B6CBB57
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C991C627-DA48-4138-B9DB-AE3D3DD45D1F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C991C627-DA48-4138-B9DB-AE3D3DD45D1F
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:C991C627-DA48-4138-B9DB-AE3D3DD45D1F
,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-10-12 14:11:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-10-12 14:11:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-10-12 14:11:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-10-12 14:11:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-10-12 14:11:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-10-12 14:11:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:198093de-0b19-48ad-b6f2-b74b8c0bed36 error: startListeningNotActive
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"t6eXOoWGMFyNWVP69JxD281Z8MmqP99X","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
,ok 130 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:11:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:09 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7B456AFF-8333-42C2-89B1-5E4F3FC40EDE
,[ThaliCore] Browser.startListening
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:11:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
,ok 132 Got null as expected
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XChJpqtAZ28j95wRyD9uVlNnhIzsjAJ8","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-10-12 14:11:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:46D1882E-1DD3-4B66-9010-1139103F5EEF
[ThaliCore] Browser.startListening
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:11:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on star,ting
,ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:11 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:11 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:e7077743-5f29-4ed3-aa22-b1d10d5f673a
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7563EA47-7507-4979-92D8-1508550C9D7E
2017-10-12 1,4:11:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E2756A13-EE78-4729-B144-17173EA110AF
[ThaliCore] Browser.startListening
2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:11:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3666918-5171-4C9E-8643-662288950CC7","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3666918-5171-4C9E-8643-662288950CC7 (syncValue: RP9t7aVpP2rz5z,PyUovUrheo7jBFpYaG)'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.conn,ectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950,CC7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471","generation":0}'
2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3666918-5171-4C9E-8643-662288950CC7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B3666918-5171-4C9E-8643-662288950CC7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3666918-5171-4C9E-8643-662288950CC7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50630
2017-10-12 14:11:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RP9t7aVpP2rz5zPyUovUrheo7jBFpYaG",,"error":null,"portNumber":50630}'
2017-10-12 14:11:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RP9t7aVpP2rz5zPyUovUrheo7jBFpYaG', error: 'null', listeningPort: '50630''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3666918-5171-4C9E-8643-662288950CC7:0
ok 143 Got null as expected
[ThaliCore] BrowserManager.co,nnectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0) found active relay
,2017-10-12 14:11:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iS3T0cRnZ5S28XBKe2R1EvcRs30mm4DE","error":null,"portNumber":50630}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0) found active relay
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3666918-5171-4C9E-8643-662288950CC7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 11, 15]
,2017-10-12 14:11:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OGg0cB3DyTkoJycv0AnNifonoWVAuJGf","error":null,"portNumber":50630}'
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:15
,ok 147 No error
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7982BFFA-C4E0-4084-AC2C-25EBE2BE4891
[ThaliCore] Advertiser: session connected Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7982BFFA-C4E0-4084-AC2C-25EBE2BE4891 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7982BFFA-C4E0-4084-AC2C-25EBE2BE4891
,[ThaliCore] Session.session(_:peer:didChange:) peer:7982BFFA-C4E0-4084-AC2C-25EBE2BE4891 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982BFFA-C4E0-4084-AC2C-25EBE2BE4891
[ThaliCore] Session.startOutputStream(with:) peer:7982BFFA-C4E0-4084-AC2C-25EBE2BE4891
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,6 [1, 11, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:16
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:15
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:16
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
,[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:7982BFFA-C4E0-4084-AC2C-25EBE2BE4891 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7982BFFA-C4E0-4084-AC2C-25EBE2BE4891
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:7982BFFA-C4E0-4084-AC2C-25EBE2BE4891
,2017-10-12 14:11:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:11:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 ,14:11:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-12 14:11:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7563EA47-7507-4979-92D8-1,508550C9D7E
2017-10-12 14:11:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:B3666918-5171-4C9E-8643-662288950CC7
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50630
[ThaliCore] Session.disconnect() p,eer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B3666918-5171-4C9E-8643-662288950CC7:0
,2017-10-12 14:11:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-10-12 14:11:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-10-12 14:11:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-10-12 14:11:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-10-12 14:11:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-10-12 14:11:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-10-12 14:11:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'listening 50634'
ok 149 Should throw
,# teardown
,2017-10-12 14:11:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:30 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'listening 50636'
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'listening 50639'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'Native Server - close'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'listening 50643'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'Native Server - close'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'listening 50648'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-10-12 14:11:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'listening 50652'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-10-12 14:11:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'listening 50656'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-10-12 14:11:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:33 - DEBUG createNativeListener: 'listening 50660'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-10-12 14:11:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
2017-10-12 14:11:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-10-12 14:11:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:33 - DEBUG createNativeListener: 'listening 50664'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2017-10-12 14:11:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-10-12 14:11:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'Native Server - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-10-12 14:11:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-10-12 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:36 - DEBUG createNativeListener: 'listening 50716'
,2017-10-12 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-10-12 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-10-12 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-10-12 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-10-12 14:11:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:38 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:39 - DEBUG createNativeListener: 'listening 50720'
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-10-12 14:11:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:40 - DEBUG createNativeListener: 'listening 50723'
ok 196 port must be in range
,# teardown
,2017-10-12 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'listening 50724'
,ok 197 second start should return same port
,# teardown
,2017-10-12 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:40 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'listening 50726'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-10-12 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-10-12 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-10-12 14:11:41 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-10-12 14:11:41 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-10-12 14:11:41 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 50728
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:766863A9-E14B-4B2C-AC66-EEF3271F0561
2017-10-12 1,4:11:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5
[Tha,l,iCore] Browser.startListening
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:11:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-10-12 14:11:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471","generation":0}'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471 (syncValue: kaqiTd9yKT49YSmo7JB4RPrieYrjzgDa)'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
2017-10-12 14:11:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3014F9AF-1D13-40A2-81E5-517A999AD0EE","generation":0}'
2017-10-12 14:11:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:42 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
2017-10-12 14:11:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DFD51C65-E602-49DB-BA9A-26A7B16A95DB","generation":0}'
2017-10-12 14:11:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-12 14:11:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6F,C9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6F,C9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:11:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kaqiTd9yKT49YSmo7JB4RPrieYrjzgDa","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:11:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kaqiTd9yKT49YSmo7JB4RPrieYrjzgDa', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:11:47 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:11:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3014F9AF-1D13-40A2-81E5-517A999AD0EE (syncValue: ljWdjSHH1UigeVH3Wy99p6F,7j2b60fEy)'
2017-10-12 14:11:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3014F9AF-1D13-40A2-81E5-517A9,99AD0EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:11:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4DA2D295-F6F0-4264-8E65-79653B414127
[ThaliCore] Advertiser: session connected Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4DA2D295-F6F0-4264-8E65-79653B414127 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4DA2D295-F6F0-4264-8E65-79653B414127
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DA2D295-F6F0-4264-8E65-79653B414127 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50738
,2017-10-12 14:11:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ljWdjSHH1UigeVH3Wy99p6F7j2b60fEy","error":null,"portNumber":50738}'
,2017-10-12 14:11:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ljWdjSHH1UigeVH3Wy99p6F7j2b60fEy', error: 'null', listeningPort: '50738''
,ok 210 should be equal
,2017-10-12 14:11:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DFD51C65-E602-49DB-BA9A-26A7B16A95DB (syncValue: P8PJLrBP2YoIqp9HduynSXsWdscin3Xk)'
,2017-10-12 14:11:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:32744408-508E-49AB-B150-13D7858EDCA4
[ThaliCore] Advertiser: session connected Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:32744408-508E-49AB-B150-13D7858EDCA4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50742
,2017-10-12 14:11:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"P8PJLrBP2YoIqp9HduynSXsWdscin3Xk","error":null,"portNumber":50742}'
,2017-10-12 14:11:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'P8PJLrBP2YoIqp9HduynSXsWdscin3Xk', error: 'null', listeningPort: '50742''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:32744408-508E-49AB-B150-13D7858EDCA4
,[ThaliCore] Session.session(_:peer:didChange:) peer:32744408-508E-49AB-B150-13D7858EDCA4 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:11:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:11:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:766863A9-E14B-,4B2C-AC66-EEF3271F0561
2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdat,e (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50738
[ThaliCore] Session.disconnect() p,eer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:32744408-508E-49AB-B150-13D7858EDCA4 state,: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPCl,ient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:32744408-508E-49AB-B150-13D7858EDCA4
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:32744408-508E-49AB-B150-13D7858EDCA4
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DA2D295-F6F0-4264-8E65-79653B414127 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:50742
[ThaliCore] Session.disconnect() peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB
,2017-10-12 14:11:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"P8PJLrBP2YoIqp9HduynSXsWdscin3Xk","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 50744
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:11:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-1,2 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:899195D7-975F-4830-8A7A-ABF48513F94C
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 215 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:22114238-337B-4DEA-B3CE-8BD17D02606B
,[ThaliCore] Browser.startListening
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:11:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserManager.foundP,eerHandler peer:Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
ok 216 Can call startListeningForAdvertisements without error
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0,
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3014F9AF-1D13-40A2-81E5-517A999AD0EE","generation":0}'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3014F9AF-1D13-40A2-81E5-517A999AD0EE (syncValue: kGWBDMNIgcX6NriYidspKxMOOOcHbRmN)'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DFD51C65-E602-49DB-BA9A-26A7B16A95DB","generation":0}'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
2017-10-12 14:11:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}'
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:59 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:30,14F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:30,14F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:30,14F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:12:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kGWBDMNIgcX6NriYidspKxMOOOcHbRmN","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:12:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kGWBDMNIgcX6NriYidspKxMOOOcHbRmN', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:12:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:12:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F53D4835-021E-4B75-99AB-2901B2A6C2E5 (syncValue: vshnKp7z5qluVemjqq9GOFl,DnreZ6HMr)'
2017-10-12 14:12:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F53D4835-021E-4B75-99AB-2901B,2A6C2E5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:12:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50761
,2017-10-12 14:12:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vshnKp7z5qluVemjqq9GOFlDnreZ6HMr","error":null,"portNumber":50761}'
,2017-10-12 14:12:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vshnKp7z5qluVemjqq9GOFlDnreZ6HMr', error: 'null', listeningPort: '50761''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-10-12 14:12:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A40386E-2B01-46CD-87DA-781E0DD5ECDD (syncValue: nCVXKjOPdwXoEto8urTLpZrNb9A8H4HF)'
,2017-10-12 14:12:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B772FC20-08B9-4154-9EA0-BECA2A84867F
[ThaliCore] Advertiser: session connected Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B772FC20-08B9-4154-9EA0-BECA2A84867F state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50767
2017-10-12 14:12:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nCVXKjOPdwXoEto8urTLpZrNb9A8H4HF","error":null,"portN,umber":50767}'
2017-10-12 14:12:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nCVXKjOPdwXoEto8urTLpZrNb9A8H4HF', error: 'null', listeningPort: '50767''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B772FC20-08B9-4154-9EA0-BECA2A84867F
,[ThaliCore] Session.session(_:peer:didChange:) peer:B772FC20-08B9-4154-9EA0-BECA2A84867F state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33
[ThaliCore] Session.session(_:peer:didChange:) peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33
,[ThaliCore] Session.session(_:peer:didChange:) peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:12:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:899195D7-975F-4830-8A7A-ABF48513F94C
2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5,
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50761
[ThaliCore] Session.disconnect() peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B772FC20-08B9-4154-9EA0-BECA2A84867F state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50767
[ThaliCore] Session.disconnect() peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD
,2017-10-12 14:12:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33
[ThaliCore] AdvertiserRelay.deinit
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nCVXKjOPdwXoEto8urTLpZrNb9A8H4HF","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-10-12 14:12:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'listening 50771'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'listening 50772'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7460C68C-5693-40F5-93A7-04BC2FD63246
[ThaliCore] Browser.st,artListening
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 230 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertis,ingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:12:24 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:12:24 - DEBUG makeIntoCloseA,llServer: 'closeAll called on server'
ok 232 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'listening 50773'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "52AD5AE9-015B-4411-8681-3D81E4EA7107", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:52AD5AE9-015B-4411-8681-3D81E4EA7107
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "52AD5AE9-015B-4411-8681-3D81E4EA7107", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:52AD5AE9-015B-4411-8681-3D81E4EA7107
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:52AD5AE9-015B-4411-8681-3D81E4EA7107
[ThaliCore] Advertiser.stopAdvertising() peerID:52AD5AE9-015B-4411-8681-3D81E4EA7107
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'listening 50776'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-10-12 14:12:26 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 241 specific error expected
,# teardown
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'listening 50777'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5C34C243-4874-4DFE-9D9D-C57DB7109796
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C997346E-2754-40D2-A1DC-66BE66A914BB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C997346E-2754-40D2-A1DC-66BE66A914BB
2017-10-12 1,4:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:C997346E-2754-40D2-A1DC-66BE66A914BB
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'listening 50780'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0252653B-C3F6-46D3-ACCA-B0B9B2F239AF
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F00D71C6-75E2-4C05-AC2F-00B2D355ED8C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F00D71C6-75E2-4C05-AC2F-00B2D355ED8C
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}]'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}]'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F00D71C6-75E2-4C05-AC2F-00B2D355ED8C
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'listening 50782'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:53AC0A8B-20D9-47F2-BCA3-B6F807250453
[ThaliCore] Browser.st,artListening
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "50CF3CCE-7B4C-464A-9C98-8C0840472C3B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,50CF3CCE-7B4C-464A-9C98-8C0840472C3B
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:50CF3CCE-7B4C-464A-9C98-8C0840472C3B
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-10-12 14:12:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-10-12 14:12:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:28 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-10-12 14:12:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-10-12 14:12:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-10-12 14:12:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-10-12 14:12:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-10-12 14:12:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-10-12 14:12:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-10-12 14:12:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-10-12 14:12:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-10-12 14:12:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-10-12 14:12:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'listening 50785'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:34C81CE1-90A6-4208-8F90-E52BB20F2496
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-10-12 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'listening 50786'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2CDB40A7-B02F-4A78-AB00-4DB03E034EF4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2CDB40A7-B02F-4A78-AB00-4DB03E034EF4
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2CDB40A7-B02F-4A78-AB00-4DB03E034EF4
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'listening 50788'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:12:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'listening 50789'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0BA71A8A-E994-4769-A9AF-D22A01CEED38
[ThaliCore] Browser.st,artListening
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,76CF7764-5163-4F9C-84F2-74BED114CDC9
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}]'
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}]'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","generation":0}]'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","generation":0}'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:76CF7764-5163-4F9C-84F2-74BED114CDC9
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:12:36 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'listening 50791'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:35C81906-6548-4B44-8317-0C0DE5CB1B6B
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F773DE60-18A4-400C-8204-9798A9B73E46
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
2017-10-12 14:12:37 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A8A,CC72-CBD4-4A4C-ACF7-A8702F78F651:0
2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}'
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}]'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","generation":0}]'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","generation":0}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:,F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F53D4835-021E-4B75-99AB-2901B2A6C2E5 (syncValue: t6V9I8iG0wCo9BiCHSBAEklGg1OLWrSM)'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:12:37 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}]'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}]'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F5,3D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
2017-10-12 14:12:40 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}]'
,2017-10-12 14:12:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}'
,2017-10-12 14:12:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-10-12 14:12:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F5,3D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:12:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"t6V9I8iG0wCo9BiCHSBAEklGg1OLWrSM","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:12:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 't6V9I8iG0wCo9BiCHSBAEklGg1OLWrSM', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:12:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:12:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A40386E-2B01-46CD-87DA-781E0DD5ECDD (syncValue: 5JzE0l2ua25ZjMexmvE516n,onv2r9SiR)'
2017-10-12 14:12:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
2017-10-12 14:12:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","generation":0}]'
2017-10-12 14:12:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","generation":0}'
,2017-10-12 14:12:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:12:44 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
2017-10-12 14:12:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}]'
2017-10-12 14:12:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
,2017-10-12 14:12:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-10-12 14:12:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3EC027BB-FE08-4A57-AA94-BE6D3AB678D0
[ThaliCore] Advertiser: session connected Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3EC027BB-FE08-4A57-AA94-BE6D3AB678D0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:12:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5JzE0l2ua25ZjMexmvE516nonv2r9SiR","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:12:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5JzE0l2ua25ZjMexmvE516nonv2r9SiR', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:12:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:12:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ABD6CB4A-6271-425B-A46F-AF3661BD6BDF (syncValue: irZ15u8zwHmbRlC0K8jSjS9,YQoTD7tTR)'
2017-10-12 14:12:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ABD6CB4A-6271-425B-A46F-AF366,1BD6BDF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3EC027BB-FE08-4A57-AA94-BE6D3AB678D0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EC027BB-FE08-4A57-AA94-BE6D3AB678D0 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3EC027BB-FE08-4A57-AA94-BE6D3AB678D0
[ThaliCore] Session.startOutputStream(with:) peer:3EC027BB-FE08-4A57-AA94-BE6D3AB678D0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,7 [1, 11, 15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:17
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:93 count:1 vsID:17
[ThaliCore] VirtualSocket.writePendingData() to write:93 written:93 count:0 vsID:17
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 179 vsID:17
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:17
,[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:17
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 117 vsID:17
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:261 count:1 vsID:17
,[ThaliCore] VirtualSocket.writePendingData() to write:261 written:261 count:0 vsID:17
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50802
2017-10-12 14:12:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"irZ15u8zwHmbRlC0K8jSjS9YQoTD7tTR",,"error":null,"portNumber":50802}'
2017-10-12 14:12:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'irZ15u8zwHmbRlC0K8jSjS9YQoTD7tTR', error: 'null', listeningPort: '50802''
,2017-10-12 14:12:48 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [1, 11, 15, 16, 17, 18]
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:18
,[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:18
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 93 vsID:18
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:179 count:1 vsID:18
[ThaliCore] VirtualSocket.writePendingData() to write:179 written:179 count:0 vsID:18
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:18
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:117 count:1 vsID:18
,[ThaliCore] VirtualSocket.writePendingData() to write:117 written:117 count:0 vsID:18
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 261 vsID:18
,2017-10-12 14:12:48 - DEBUG testUtils: 'Got response data'
,2017-10-12 14:12:48 - DEBUG testUtils: 'Got end'
,ok 279 response body should match testData
,ok 280 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:68753756-18AD-45B3-83C4-613448A34424
[ThaliCore] Advertiser: session connected Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:68753756-18AD-45B3-83C4-613448A34424 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:68753756-18AD-45B3-83C4-613448A34424
,[ThaliCore] Session.session(_:peer:didChange:) peer:68753756-18AD-45B3-83C4-613448A34424 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68753756-18AD-45B3-83C4-613448A34424
[ThaliCore] Session.startOutputStream(with:) peer:68753756-18AD-45B3-83C4-613448A34424
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,9 [1, 11, 15, 16, 17, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:19
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:93 count:1 vsID:19
[ThaliCore] VirtualSocket.writePendingData() to write:93 written:93 count:0 vsID:19
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 179 vsID:19
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:19
,[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:19
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 117 vsID:19
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:261 count:1 vsID:19
,[ThaliCore] VirtualSocket.writePendingData() to write:261 written:261 count:0 vsID:19
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F773DE60-18A4-400C-8204-9798A9B73E46
2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-10-12 14:12:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-10-12 14:12:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeS,treams() vsID:19
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [1, 11, 15, 16, 18, 19]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] VirtualSocket.deinit vsID:19 [1, 11, 15, 16, 18]
,ok 281 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50802
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:18 [1, 11, 15, 16]
,[ThaliCore] Session.disconnect() peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
[ThaliCore] Session.session(_:peer:didChange:) peer:68753756-18AD-45B3-83C4-613448A34424 state: connected -> notConnected
[T,haliCore] Advertiser: session notConnected Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] Advert,iserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:68753756-18AD-45B3-83C4-613448A34424
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EC027BB-FE08-4A57-AA94-BE6D3AB678D0 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"irZ15u8zwHmbRlC0K8jSjS9YQoTD7tTR","error":"Session disconnected","portNumber":null}'
,# can still do HTTP requests between peers with coordinator
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'listening 50805'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CC84257A-D8B4-422A-93BC-E0349FBA3B0B
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:410E7270-6EDA-4ECB-8986-F94E54BD9FA2
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:12:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Session.deinit peer:68753756-18AD-45B3-83C4-613448A34424
[ThaliCore] Session.deinit peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
2017-10-12 14:12:59 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}]'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
2017-10-12 14:12:59 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 81780A6B-66B6-4FF1-8B15-F2911B9E5A76 (syncValue: ZeJoerK58c16BK3,umD3G4jAdlJXNIoFZ)'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81,780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}]'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}]'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailab,le":true,"generation":0,"portNumber":null}'
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
2017-10-12 14:12:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"pee,rIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E,0DD5ECDD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}]'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-10-12 14:12:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}]'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","generation":0}]'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","generation":0}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
2017-10-12 14:13:07 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}]'
2017-10-12 14:13:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}'
,2017-10-12 14:13:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:13:07 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:13:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZeJoerK58c16BK3umD3G4jAdlJXNIoFZ","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:13:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZeJoerK58c16BK3umD3G4jAdlJXNIoFZ', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:13:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:13:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A40386E-2B01-46CD-87DA-781E0DD5ECDD (syncValue: TYTRY9lqlCQd32acMhXD5FY,iy42v4BZQ)'
2017-10-12 14:13:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A40386E-2B01-46CD-87DA-781E0,DD5ECDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
2017-10-12 14:13:16 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}]'
2017-10-12 14:13:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
,2017-10-12 14:13:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:13:16 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2A40386E,-2B01-46CD-87DA-781E0DD5ECDD error: max retries exceeded
2017-10-12 14:13:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TYTRY9lqlCQd32acMhXD5FYiy42v4BZQ","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:13:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TYTRY9lqlCQd32acMhXD5FYiy42v4BZQ', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:13:18 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:13:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D7CAB270-9BC0-4CDF-BD73-40FA14990958 (syncValue: eBVQcTB,c3n0UBeRr4Sl0bkrr1jvcPXsl)'
2017-10-12 14:13:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D7CAB270-9BC0,-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50825
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eBVQcTBc3n0UBeRr4Sl0bkrr1jvcPXsl","error":null,"portNumber":50825}'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eBVQcTBc3n0UBeRr4Sl0bkrr1jvcPXsl', error: 'null', listeningPort: '50825''
,2017-10-12 14:13:22 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 11, 15, 16, 20]
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:20
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:20
,[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:20
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:20
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 93 vsID:20
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:179 count:1 vsID:20
,[ThaliCore] VirtualSocket.writePendingData() to write:179 written:179 count:0 vsID:20
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:20
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:20
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:117 count:1 vsID:20
[ThaliCore] VirtualSocket.writePendingData() to write:117 written:117 count:0 vsID:20
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:20
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 261 vsID:20
,2017-10-12 14:13:22 - DEBUG testUtils: 'Got response data'
,2017-10-12 14:13:22 - DEBUG testUtils: 'Got end'
,ok 282 response body should match testData
,ok 283 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:410E7270-6EDA-4ECB-8986-F94E54BD9FA2
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:13:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12, 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:13:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 284 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50825
[ThaliCore] VirtualSocket.closeStr,eams() vsID:20
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] Session.disconnect() peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:20 [1, 11, 15, 16]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-10-12 14:13:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:13:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:13:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:13:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 286 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:13:23 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:13:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:13:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:13:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'listening 50827'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D642EDF8-5839-47D5-B7F7-2922EAF29D6C
[ThaliCore] Browser.startListening
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:13:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:13:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D5C8287F-80CD-4EE0-B744-DD990FEE672B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D5C8287F-80CD-4EE0-B744-DD990FEE672B
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:13:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-10-12 14:13:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:13:24 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
2017-10-12 14:13:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}]'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
2017-10-12 14:13:24 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D7CAB270-9BC0-4CDF-BD73-40FA14990958 (syncValue: VBde0DeHjmPMD1Rn72LWez0Xlr4UCsB0)'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","generation":0}]'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","generation":0}'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: 0)
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FB421661-2DB1-4A56-B4CE-BFB2D97775BD","generation":0}]'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FB421661-2DB1-4A56-B4CE-BFB2D97775BD","generation":0}'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FB421661-2DB1-4A56-B4CE-BFB2D97775BD","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:13:24 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FB421661-2DB1-4A56-B4CE-BFB2D97775BD","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"FB421661-2DB1-4A56-B4CE-BFB2D97775BD","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5C8287F-80CD-4EE0-B744-DD990FEE672B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5C8287F-80CD-4EE0-B744-DD990FEE672B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F7B780B3-E5D5-4724-94CC-B034C67019CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F7B780B3-E5D5-4724-94CC-B034C67019CD", generation: 0)
,2017-10-12 14:13:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F7B780B3-E5D5-4724-94CC-B034C67019CD","generation":0}]'
2017-10-12 14:13:25 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F7B780B3-E5D5-4724-94CC-B034C67019CD","generation":0}'
,2017-10-12 14:13:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F7B780B3-E5D5-4724-94CC-B034C67019CD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:13:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F7B780B3-E5D5-4724-94CC-B034C67019CD","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:13:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F7B780B3-E5D5-4724-94CC-B034C67019CD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:13:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D7,CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
2017-10-12 14:13:27 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","generation":0}]'
2017-10-12 14:13:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","generation":0}'
,2017-10-12 14:13:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:13:27 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D7,CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:13:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D7,CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D7,CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:D7CAB270,-9BC0-4CDF-BD73-40FA14990958 error: max retries exceeded
2017-10-12 14:13:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VBde0DeHjmPMD1Rn72LWez0Xlr4UCsB0","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:13:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VBde0DeHjmPMD1Rn72LWez0Xlr4UCsB0', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:13:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:13:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FB421661-2DB1-4A56-B4CE-BFB2D97775BD (syncValue: l3J6sgE,zIiA76nG4Z2T52FnfZVtdt0uy)'
2017-10-12 14:13:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FB421661-2DB1,-4A56-B4CE-BFB2D97775BD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0 state: notConnected -> connecting
,2017-10-12 14:13:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AD16D2A5-CF05-4471-8954-790D54808257
[ThaliCore] Advertiser: session connected Peer(uuid: "D5C8287F-80CD-4EE0-B744-DD990FEE672B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AD16D2A5-CF05-4471-8954-790D54808257 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
2017-10-12 14:13:38 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}]'
2017-10-12 14:13:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}'
,2017-10-12 14:13:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:13:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50844
2017-10-12 14:13:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"l3J6sgEzIiA76nG4Z2T52FnfZVtdt0uy",,"error":null,"portNumber":50844}'
2017-10-12 14:13:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'l3J6sgEzIiA76nG4Z2T52FnfZVtdt0uy', error: 'null', listeningPort: '50844''
2017-10-12 14:13:38 - WARN thaliMobileNativeTestUti,ls: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 11, 15, 16, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:21
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:21
,[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:21
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:21
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 93 vsID:21
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:179 count:1 vsID:21
[ThaliCore] VirtualSocket.writePendingData() to write:179 written:179 count:0 vsID:21
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:21
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:21
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:117 count:1 vsID:21
,[ThaliCore] VirtualSocket.writePendingData() to write:117 written:117 count:0 vsID:21
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:21
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 261 vsID:21
,2017-10-12 14:13:39 - DEBUG testUtils: 'Got response data'
,2017-10-12 14:13:39 - DEBUG testUtils: 'Got end'
,ok 287 response body should match testData
,ok 288 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AD16D2A5-CF05-4471-8954-790D54808257
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD16D2A5-CF05-4471-8954-790D54808257 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AD16D2A5-CF05-4471-8954-790D54808257
[ThaliCore] Session.startOutputStream(with:) peer:AD16D2A5-CF05-4471-8954-790D54808257
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,2 [1, 11, 15, 16, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:22
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:22
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:93 count:1 vsID:22
[ThaliCore] VirtualSocket.writePendingData() to write:93 written:93 count:0 vsID:22
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:22
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 179 vsID:22
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:22
,[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:22
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:22
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 117 vsID:22
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:261 count:1 vsID:22
,[ThaliCore] VirtualSocket.writePendingData() to write:261 written:261 count:0 vsID:22
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:22
,2017-10-12 14:13:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:13:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-10-12 14:14:39 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-10-12 14:14:39 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-10-12 14:,14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-10-12 14:14:39 - INF,O CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-10-12 14:14:39 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - can do HTTP requests after connections are cut, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1,-F62A39333844/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/bluebird/js/re,lease/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-10-12 14:14:39 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-10-12 14:14:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:59 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:350:16
$9@timers.js:120:1
''
,2017-10-12 14:17:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4,CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4,CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4,CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4,CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4,CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4,CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4,CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:28:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CC,F-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:28:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/4961F667-C122-4CCF-95A1-F62A39333844/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
