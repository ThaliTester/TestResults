#### Test 11335185196ab692_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6DA3DB86-DE3D-4A77-A085-A856B7592F1E/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/6DA3DB86-DE3D-4A77-A085-A856B7592F1E/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63624"
,(lldb)     command script import "/tmp/6DA3DB86-DE3D-4A77-A085-A856B7592F1E/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
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
,2017-07-13 07:38:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:38:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:38:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:38:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:38:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:38:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:38:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
,AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7195D958-E21B-4DE9-9FED-5F58EFDB501E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7195D958-E21B-4DE9-9FED-5F58EFDB501E
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:935972AD-CDBD-42BB-A21C-,A171583DE537
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:fo,undPeer:lostPeer:) peer:B35E8FD9-16A1-4C8E-94BF-CDBC07325ADC
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7A790ED8-5708-4B31-912D-1534CCEE28AB", generation: 0)
[Tha,liCore] Advertiser.startAdvertising with peerID:7A790ED8-5708-4B31-912D-1534CCEE28AB
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7A790ED8-5708-4B31-912D-1534CCEE28AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7A790ED8-5708-4B31-912D-1534CCEE28AB", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-13 07:38:18 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.871132016181946
,2017-07-13 07:38:18 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-07-13 07:38:18 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7A790ED8-5708-4B31-912D-1534CCEE28AB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7A790ED8-5708-4B31-912D-1534CCEE28AB", generation: 0)
,2017-07-13 07:38:21 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-13 07:38:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-13 07:38:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-13 07:38:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-13 07:38:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-13 07:38:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-13 07:38:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-13 07:38:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-13 07:38:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-13 07:38:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-13 07:38:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-13 07:38:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-13 07:38:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-13 07:38:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-13 07:38:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-13 07:38:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-13 07:38:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-13 07:38:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-13 07:38:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-13 07:38:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-13 07:38:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-13 07:38:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-13 07:38:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-13 07:38:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-13 07:38:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-13 07:38:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-13 07:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-13 07:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-13 07:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-13 07:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-13 07:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-13 07:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-13 07:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-13 07:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-13 07:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-13 07:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-13 07:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-13 07:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-13 07:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-13 07:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-13 07:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-13 07:38:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-13 07:38:25 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-13 07:38:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A4,4-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A4,4-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:38:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A4,4-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:38:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A4,4-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:38:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A4,4-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:38:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:39:00 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-13 07:39:00 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-13 07:39:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-13 07:39:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-13 07:39:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-13 07:39:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-13 07:39:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-13 07:39:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-13 07:39:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-13 07:39:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
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
,2017-07-13 07:39:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-13 07:39:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-13 07:39:33 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-13 07:39:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-13 07:39:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1A16068C-9152-45BE-A549-3B3D46E7D83B
[ThaliCore] Browser.startListening
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-13 07:39:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AF5E4467-4280-4700-9502-58D635A6B48E
,[ThaliCore] Browser.startListening
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 07:39:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 07:39:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9DCCBEA0-AF78-44CD-99B1-F8616D8317A9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9DCCBEA0-AF78-44CD-99B1-F8616D8317A9
2017-07-13 0,7:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 76 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E2621DEC-631C-4B4D-857F-A58B1DA3511B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E2621DEC-631C-4B4D-857F-A58B1DA3511B
2017-07-13 0,7:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E2621DEC-631C-4B4D-857F-A58B1DA3511B", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:E2621DEC-631C-4B4D-857F-A58B1DA3511B
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 84 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:07BA770A-1623-4693-8CFA-B9750DA025BA
2017-07-13 0,7:39:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:85840493-C363-4C9E-AC91-306BD13663A6
[Thali,C,ore] Browser.startListening
2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 07:39:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:39:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:668BFA24-1C83-4C25-A698-52B1925BCC32:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "668BFA24-1C83-4C25-A698-52B1925BCC32", generation: 0)
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07BA770A-1623-4693-8CFA-B9750DA025BA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 07:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 93 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DF43B91C-BBA8-4DB3-99C5-7CF7E5038090
2017-07-13 0,7:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:89EC8445-330D-46BF-9B57-E0928F563ED2
[Thal,i,Core] Browser.startListening
2017-07-13 07:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 07:39:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 07:39:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0)
2017-07-13 07:39:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87","generation":0}'
2017-07-13 07:39:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87, (syncValue: 4AB8Ul31mQxIBN4abgDHsEehC2F266aA)'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:668BFA24-1C83-4C25-A698-52B1925BCC32:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "668BFA24-1C83-4C25-A698-52B1925BCC3,2", generation: 0)
2017-07-13 07:39:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0) new relay
[Thali,Core] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 07:39:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"668BFA24-1C83-4C25-A698-52B1925BCC32","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0)
[ThaliCore] Session.disconnect() peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:668BFA24-1C83-4C25-A698-52B1925BCC32:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "668BFA24-1C83-4C25-A698-52B1925BCC32", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
2017-07-13 07:39:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"65A3BFA4-3808-4AFD-9773-59BA8C46E2F8","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
2017-07-13 07:39:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF43B91C-BBA8-4DB3-99C5-7CF7E5038090:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4AB8Ul31mQxIBN4abgDHsEehC2F266aA","error":"Connection could not be established","portNumber":null}'
201,7-07-13 07:40:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4AB8Ul31mQxIBN4abgDHsEehC2F266aA', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'Receiv,ed peer availability changed event with {"peerIdentifier":"62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEv,ent due to not being in started state'
,2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] Session.disconnect() peer:6,2B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0)
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
,2017-07-13 07:40:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 07:40:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 65A3BFA4-3808-4AFD-9773-59BA8C46E2F8 (syncValue: A2lrCqKNcLg8AJc1KtHiW6HtsP7RZ6Rl)'
,2017-07-13 07:40:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49667
2017-07-13 07:40:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"A2lrCqKNcLg8AJc1KtHiW6HtsP7RZ6Rl","error":null,"portNumber":49667}'
,2017-07-13 07:40:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'A2lrCqKNcLg8AJc1KtHiW6HtsP7RZ6Rl', error: 'null', listeningPort: '49667''
,2017-07-13 07:40:04 - INFO testThaliMobileNative: ''
ok 97 Must have listeningPort
ok 98 listeningPort must be a number
ok 99 listening port should not be 0
,# teardown
,2017-07-13 07:40:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 07:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49667
[ThaliCore] Session.disconnect,() peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
,# setup
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 102 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C2E4F2C6-B29F-47CC-A5CC-2EC5EA30AB25
[ThaliCore] Browser.startListening
2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
2017-07-13 07:40:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"65A3BFA4-3808-4AFD-9773-59BA8C46E2F8","generation":0}'
,2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 65A3BFA4-3808-4AFD-9773-59BA8C46E2F8 (syncValue: gMLkOHc89lK5ryfyrnzzsh2dXaeWdIk6)'
,2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0770DD0B-3938-42AB-BD22-0A1EE963ACCD", generation: 0)
2017-07-13 07:40:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0770DD0B-3938-42AB-BD22-0A1EE963ACCD","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:883F5BBE-EDEE-48D4-A797-D586985545C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "883F5BBE-EDEE-48D4-A797-D586985545C4", generation: 0)
,2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"883F5BBE-EDEE-48D4-A797-D586985545C4","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
[ThaliCore] Session.disconnect() peer:65A3BFA4-380,8-4AFD-9773-59BA8C46E2F8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", genera,tion: 0)
2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gMLkOHc89lK5ryfyrnzzsh2dXaeWdIk6","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:13 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'gMLkOHc89lK5ryfyrnzzsh2dXaeWdIk6', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"65A3BFA4-3808-4AFD-9773-59BA8C46E2F8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13, 07:40:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"65A3BFA4-3808-4AFD-9773-59BA8C46E2F8","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0770DD0B-3938-42AB-BD22-0A1EE963ACCD (syncValue: vsTqbP8sg5GF1mskPAobhLCAzwsHGgeB)'
2017-07-13 07:40:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0770DD0B-3938-42AB-BD22-0A1EE963ACCD", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0770DD0B-3938-42AB-BD22-,0A1EE963ACCD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9B30D020-EBDA-44F9-9AEA-4C3DBC19223F
[ThaliCore] Advertiser: session connected Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9B30D020-EBDA-44F9-9AEA-4C3DBC19223F state: notConnected -> connecting
,[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "0770DD0B-3938-42AB-BD22-0A1EE963ACCD", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49674
,2017-07-13 07:40:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vsTqbP8sg5GF1mskPAobhLCAzwsHGgeB","error":null,"portNumber":49674}'
,2017-07-13 07:40:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vsTqbP8sg5GF1mskPAobhLCAzwsHGgeB', error: 'null', listeningPort: '49674''
,Connecting to the localhost:49674
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
Connected to the localhost:49674
2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes,):'
,2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] Session.startOutputStream(with:) peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9B30D020-EBDA-44F9-9AEA-4C3DBC19223F
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B30D020-EBDA-44F9-9AEA-4C3DBC19223F state: connecting -> connected
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9B30D020-EBDA-44F9-9AEA-4C3DBC19223F
,[ThaliCore] Session.startOutputStream(with:) peer:9B30D020-EBDA-44F9-9AEA-4C3DBC19223F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 104 got the same data ,back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 [2]
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A1B3E12-2EEA-4C75-9FE2-281E313FFE3E
[ThaliCore] Advertiser: session connected Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2A1B3E12-2EEA-4C75-9FE2-281E313FFE3E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2A1B3E12-2EEA-4C75-9FE2-281E313FFE3E
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A1B3E12-2EEA-4C75-9FE2-281E313FFE3E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2A1B3E12-2EEA-4C75-9FE2-281E313FFE3E
[ThaliCore] Session.startOutputStream(with:) peer:2A1B3E12-2EEA-4C75-9FE2-281E313FFE3E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 07:40:23 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-13 07:40:23 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 07:40:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-13 07:40:23 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disco,nnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 07:40:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 ,07:40:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-13 07:40:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:40:23 - INFO thaliMobile: 'Filtered out discoveryA,dvertisingStateUpdate (was in stopped state).'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49674
,[ThaliCore] Session.disconnect() peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B30D020-EBDA-44F9-9AEA-4C3DBC19223F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2A1B3E12-2EEA-4C75-9FE2-281E313FFE3E
[ThaliCore] Sessio,n.deinit peer:2A1B3E12-2EEA-4C75-9FE2-281E313FFE3E
[ThaliCore] Session.session(_:peer:didChange:) peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "0770DD0B-3938-42AB-BD22-0,A1EE963ACCD", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "0770DD0B-3938-42AB-BD22-0A1EE963ACCD", generation: 0)
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:40:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5
,2017-07-13 07:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 07:40:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 07:40:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 107 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A
,[ThaliCore] Browser.startListening
,2017-07-13 07:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 07:40:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 07:40:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:883F5BBE-EDEE-48D4-A797-D586985545C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "883F5BBE-EDEE-48D4-A797-D586985545C4", generation: 0)
2017-07-13 07:40:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"883F5BBE-EDEE-48D4-A797-D586985545C4","generation":0}'
2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 883F5BBE-EDEE-48D4-A797-D586985545C4, (syncValue: K06r2LqxlRDoxRqtpSZmWncGqZndxejb)'
2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "883F5BBE-EDEE-48D4-A797-D586985545C4", gen,eration: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "883F5BBE-EDEE-48D4-A797-D586985545C4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:883F5BBE-EDEE-48D4-A797-D586985545C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0770DD0B-3938-42AB-BD22-0A1EE963ACCD", generation: 0)
2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"F7974F8D-9A8D-4B97-8930-80FC4382D89E","generation":0}'
,2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0770DD0B-3938-42AB-BD22-0A1EE963ACCD","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0)
2017-07-13 07:40:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"724A47F8-A6A9-4ACB-88A5-C246773D2521","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:883F5BBE-EDEE-48D4-A797-D586985545C4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "883F5BBE-EDEE-48D4-A797-D586985545C4", generation: 0)
[ThaliCore] Session.disconnect() peer:883F5BBE-EDE,E-48D4-A797-D586985545C4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:883F5BBE-EDEE-48D4-A797-D586985545C4:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "883F5BBE-EDEE-48D4-A797-D586985545C4", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:883F5BBE-EDEE-48D4-A797-D586985545C4:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "883F5BBE-EDEE-48D4-A797-D586985545C4", genera,tion: 0)
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"K06r2LqxlRDoxRqtpSZmWncGqZndxejb","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'K06r2LqxlRDoxRqtpSZmWncGqZndxejb', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"883F5BBE-EDEE-48D4-A797-D586985545C4","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,07:40:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"883F5BBE-EDEE-48D4-A797-D586985545C4","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F7974F8D-9A8D-4B97-8930-80FC4382D89E (syncValue: vQHUOGV,kJgvTwiswaxmzqrNyP4ipt5cj)'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89,E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0770DD0B-3938-42AB-BD22-0A1EE963ACCD", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49684
,2017-07-13 07:40:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vQHUOGVkJgvTwiswaxmzqrNyP4ipt5cj","error":null,"portNumber":49684}'
,2017-07-13 07:40:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vQHUOGVkJgvTwiswaxmzqrNyP4ipt5cj', error: 'null', listeningPort: '49684''
,Connecting to the localhost:49684
,Connecting to the localhost:49684
Connecting to the localhost:49684
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] TCPListener.socket(_:didAcce,ptNewSocket:)
[ThaliCore] Session.startOutputStream(with:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] Session.startOutputStream(with:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
Connected to the localhost:49684
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
,Connected to the localhost:49684
,Connected to the localhost:49684
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 4, 5]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 4, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 112 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [2, 5, 6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 113 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStream,s() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [2, 6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [2]
,ok 114 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43
[ThaliCore] Advertiser: session connected Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43
,[ThaliCore] Session.session(_:peer:didChange:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43
,[ThaliCore] Session.startOutputStream(with:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43
,[ThaliCore] Session.startOutputStream(with:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43
[ThaliCore] Session.startOutputStream(with:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [2, 7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received (10909 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received (5404 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received (4410 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [2, 8, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
,[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [2, 8]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server received all data: US43h7LSv5BK8LSzLmaQyn1ij9kTv4o7gqE4e0kUCSxBUxRcUQDGCT4jvNolTEr82tCDdxcJUAK6uwoy65ZQeYU8liVbbQeR0FnYUah0OQ0iGGpRcL257V4l05J69kADKOSpfjd7arg1SUwo0d2eqvzbP4Nrcr3Nat3cKVRwivqLiXdYH2,s9W4zpMIIurKmhfOaJqH004voVkZTWUSaF7JSCEy74giFRO2UWrflFsMZQ7TcpKNcsnKWjAvG5eknoVyK72TNDzAFIh5ZxmKzpSmjpNG4hLlaqBv4KRyP5qnq2cq8etLFDdtscCZM5Kbk8MstsOa8GFWvSgGAQskINByS9Ja1jgOuA1CJVlIvnmiATjwgNIMknkrjSNc9UGuec8I63U6QP7UPyRdnw61iMd99T1hksBYUhR7mLVNB74tFh94p8TN,jb5t7OQ4qoIFTrC737xHDv88qoVkq8NBbMe5nZ7O5X7rahv6GNyhYElg1iHBdWgIXjxHQIYVF19dZh5PTyGxKgms3A8oYdLzSYiwura383oWj5Q1mFSViM24o42Sn1Fb9LSdW96ylifh6IPQKMN4evUgtfqqw9nDamcGD1hkddj5OOmsVoVp9RhJgJeAxhVueH16tOdFgAXRHaoFjXN7tLDwZDaNtNEydYV8D5DaTGKwZeSVAuEqK3eoSR6MsAay,waXb0n3nKcsyN9jSAowUVjYHdDWQvBen6S9E7SBEMuSuTxom73JeAPsmaNpAmSahl5TuIsjwGDapiwihBmLlxav7VCoT3ctTV5whypTVC4u8jYB9oybuvvOZtFjK6ltyiZ0TeS5KGc0IvkvpYhdT8ud10YK375MYRq0cwVaNMDP8jfMUHCtqNc6upXaiLFTs3tDUJFv93UomLoGouj0YOKEjPrXbBzUXVqxM8c9kPDcP1XnpcHgKFGnWBCIvsGHs,IiPARMYIrvKXstpLFYBfeYSUtr8ikQHHYF6Q7gxFeuq2udOkRG7ptHs3XCRpQMyILRN6ijXeB1SMNXuOs66U4cvRc1lVS7fWik6zzskWCBxwpUURY7Aq5U8VQiOHE6bfijeQ8jr4BtQLCvMixOfrQIUOIXo4E4r52SloQSdCowDWJMtq7cTK62fWbdFEElObnxBKxh3HRidbroxjAbbS3WMzLU27N3Xkcn9kRkznihzGreWfekAUo8jBjfa1Ifcf,6ABZ4sDvceH9tYwKagoluv926dRXYsBxN05GO6K0mLtBlXGyKvuPONGLAFxrvfgLuzpBJ34TYcqZuOx80y9onhOFTmYRbOWWcSl0mlXWQw6OE2TmRz0buONyu9WsoQq5IHsQc0DX2nE7VJ20AFFhZhIuOAGglSeTYViaSolDgiJTxeLGZ1q2ts7NNHGX1vdHGvGksfUDJRg6uWfexy7rHS3DsxHV6o2ndahimj4F3zW2v2cTnEVAontOUGGLmbIh,I5xyDaO8diDqz4RPlvslXdtaMUHB666EkcVlma81THzYN9ljtfA2RFToiG65oeNuCfon0YqNEnPeQwWXG1jIxA6qL158MwnoLEcbPWLu9xlswVh7Lb6LbudWvzpwkBM4Cros7Fwk9n2m77GiKao0ieo7teP2Ug0BQy1eHWArGs2LHrq4E7POWX96DCofYbDAH7I5ilsuP2WmvQZYFMevC9r7BQvLC2YrxomD1z0RxR8VYyaBEN0BMm8IEbTC4cCp,F4V7m2xszOrTBl7dqgCL7K61G9L1OSusBirqbU4vj7qh1RxKubYHGsFhFMcJwBaEQNPjBs4g8Jh1gtjiLtkx3V6dhFnArXHftswuFuPiq2X1fwsl0sfDVFOGIjClHdoA2ykag3QIB0pY4nJ5m9CjSSe1tOe6C80hf11zeGW3neh1rV2AIUovX6B0K1KgNJhTHKRVOzO39ipOdK4UZkwhtfaKVpKo1QY2QZ49lvt8nrEUxRXsEUZhvM0J6kuJbde8,kCsUKDWUwpUghODGw6RtpgCWgEiBbIfyWVOkfZ6npe0xo14ybpZXzwPM0wBiivQDYmDwv9RgxSIWCyyu741rRoYx0HaTBtUBc9LgH9Mfa8bQMaf0Br25NSKIxsFouWyv5jwPQmatHxxGPswg6xUXUFiTQQhIoEhsW7kHaShNKzZTOt5ncDeeaYblp38bEgZ4B1pBvrgDPkJnRqaWhsKgOBOP7kshTUaM7DMBTw1NxQseeCs48ewjokhdYIosCYca,JAXypeonzOuFctzoMMTsodvXbgvCMyTxYEXhXhCDDRF5ig9d0rtjxHpaEeWzKj12SCQb9rwD6UMqyU6uYcl0dPdVy6BbzdtkbaDBNWqWL4R5YNLeDYED9dQd9eeiUW8cd8vj2a6MmZGDWmiHxMFtZccJ0yw9qoXw5GIDilceNlCuqBMv5RrqXeugs4oY5NJe5NUdmrsEvvAMmhyzCppRq4aP93AmZPJ13fhnE0qCzOigR7ReGydPRlbPpweJguSn,dPkb1nuTdAipEySfjUIFIovOXVrAKhHefpxJwBBXQZsCGASGyU5hDYQqtGLbyzHbNeH5tMsdHLCaG5kbPUSIH1bV1G68xDJuarRaX13LIjto8TQF2lV5XL8j5ekp1D2Iw2xdOtwba7Nvne0kPCxsxqhie2wW7mn93aw1McHJSrhVJD5uMFygvSaEUYVzbkEg7lff4hJwGYRSOxWNid5xnJRSrTPcesiMP0N3Z7k10hiIcgjX1ERXaYAmXdw1IrBJ,Z8SUKkDfY9lNSx1u3VJIO5jxWwXZsqS9t9IE1Zp938kv24aM6QLk9iJby620LSJz8GXg5QYnMaiFg0BGdRbiyulNwJQwwiNCGtgMeEFVtMpYWZFSveDN5eLQjOfzUTPRd5pIg1NpqtQNCZav8xw1Vmia7LoqmOpi9hJ082SDI9rNquMS8l0Vjm3H9y6b3E1gquRY4hIJR4GO8t67b2KhA9oL93XZf5eehZ42ktFGiO51pbzZ74i466VxkDTMrQ2T,f2TwPZnEz6f9fgUelq2IiopZWuyxq2ANd7vQCEXz36Qg8TgNoh9LlpZpyPqxA0ivgbs7CI1OAYwv31MhyJTkdUe29wZ1IvbmiNXqc0NM5X3taIDX4x1jta6SncSsM8raA6MX7QO2jJnTrUsKRdJokV5gGW2TJQfRA0qcalfOqBegzA8CgmqHlQ7Sj8puf8imiTj7isbhaGa1Sn7KewigELcahKSnebmxhMbRkJZwQxmXa0GpZn7OJxg5ay87ZnfN,wcyDz0cXRlzv9Xy2WKKqRE90cqrHKqsQCANtszPzkjgkhGLq1gX0157WUaiLrE3yKf20r4CqZ5nhr17Qt7vOfiAcsG4ghoaWhgggc7kdvYCZo8vzISudtax86rdi3uwW3tUpN038NQ9yLVn7gsMhSviIePzqxpiau8OqarZ5obSXfxmITcCTvkBQJb2W6BeFw6ns2UI5eykJ2o3dpac19cEXvUttbqqX746nqFZTldgA20fLh1W9qnza9dE9JazT,Kn2dCdcVVObFGl1M6l12xrDuYS4FJIqTgCwHE81unBXHdsNptyVSGMoR8gzO7Zles6CsHDd0l8FEtPMU2NXRBhetu2TOX3OarxtU9RDvBRz0uEBgAyEaG7surgDRKWfMsvrmju6eGtznbsvEAE4mbMdeJtmawC1NMnmJJojgEawcc4stHFAR9HVuLpw4pDarPj1tLc2JPuvfx6KoyorQQW8HuHkYvUmL1O9DmVFgARouefje8oCWoxg3cdadHIMl,4XFtR920eYSN9eDG4k5jLZNRdoyxhQbmj8Bstbctay6LmvcMrQhBPeCT7fmCBEkX81eLPK9PszLU2fia5sD99Xc5Zf3BK26dGsXFrMQjzJ3TUiFfWSc3J79EMd3ZkQuGH5iz2CSOGlbC1nUJV3wqMPFTb7ucGw8kHjBd17GwuKB1G6pHvjZ8b1BNEZ93Enjy489jClexERFAKej0LEv5xfO3EzgBVu2zLqFJ3H7LcLQPIPlFVBTIa0kEw4MlhfoQ,E9z4p7xE9JVopBoPb2D5xfgoyZKhipyNCCFzQR4bqTeyMdBXQZOX14bIsY3Vfwz2XGT38GP5seBpPDFM7TgsNstrlIdxaLrnYxFO8tYolVjhOHuIp5DWPz8iTrQQD5KxkbUmUTRwJX8DmEwqvmOvaQRx1Rked1VY27Lw2nJUzJYDmqxC4U68TsxHRtxzKCZsRsX4TJwkH426jTS4f9Bl6w76MeUKKDnE8eVLT2P35W8TYWufB6idySAm5UjDXtrV,u8QOpL3bQojt8mAfMrEsg2CloPPuUIdcpwg4Pe5OLzjfWymNBmMz3OHQfVUtthegDD8oDJPeja1aHbzt5P7T03cKoru3CAtBgqMcfs3jqrC3oKtveh2r7YDpnlDmfh77Srw85i88LbVco4HAf28rNr55A4TnEtoGZDqz8zEqvhKlkSqjI1T74yhehdmONtBC08EhQnV1dW6Xlsx6nyfcULOlfRqhj0xZM31pzrG8axL4R4i4IRhgqkRXhUXlnMRU,ZBaz4b6KdvxeI3fBL8uot05aeskkRYRxcqpeaX0T02UVQkE1Lw1t9tK4t8kYGz8oYu8nWKtF0Orpzjd0bk2lAeqCVNy21ZBHlYY3eWWrdgz44EVx2I86YdF2OcACu9m4ycn0nYi43bQjAw0vM0hb3X0GeU2cQmCnc0cAYojKRDJqnOOrjCNyjvEgXY83yYS0x8yyDeuxoK6zv6rKS6IJp6C3bQOhC0MqcSvm9Oo8IklVcZPzQM2LOFsO7wMxbRqc,xabunI6e9x97mapg6jymx57ow3NW1CZbA47MZlg7gL9FXGVwFtGW6psTp3SeVZTxlNvFbwoZ683LIaBpcJKdS4vuKIPz9VewFOZPIk5etkVXennLdXhj0BE4ni8xKmWve6k7WfhFtWvl1RCa0SiZLnHlGX3BN3ZmPkIcVyxnEAnvoefa3CeSArUnZrCTj0bKG0ZFefB8Waw0qLuc42n6IFIgSoHtICMVRHstRdHqr7rl1rTZ4FIOj2HRPjfq20lo,J2UAI85lpiO45XmjPcCREgLG0Q9jc70t6D4C9Bhe8cRvV0LJtsVJt08kV4RjwhjkZswBsyPDTcOTWxQZdqRKxKbQ991FQWczSXHfM9HdzZSvP9jLDtWrdnFkuteYPHYeUlsbfbQTNYeKtr0QB2I9friCLMvhkG4n5zka61w0W0Oc8cq2uflqrfs0OUqq4Uzpx7Hh43AjIaC4sMmQrhsaxFXtHCFBaBbASqzA0UHzBZ4Um9E2UXJQODDtpH9bGzdS,UbXwa9XqvSddnedkzAQ4NY9uMNS1Lm2ZrLlXNHZOY8QPPTFBP5ecTE9UQeVM7p1hCK3sDH8JJmknPxYB0N3sYjVyPSEtlUY2qbUpF6XuyXJzmaDEPQQk6HrJGUMvoKJb00LRTYjvWmugO5BiEAmvHTuIzB7cnEvnlqQdrIELkWNioXLfukQtzTXm6bCiXA9yyZidBvvOvfIW58V3jqakdgoA4KXHtmTDaB1mWe4jZnJtUSlVq5QYkIGgm42scE26,oDMF2NdIMxdGTwkgn0IkLGL4I5l7BSmyM2vUN06WCkToP8igfx7TgAa33pDlwfsVO4d1t51So9Wj0AoVPUxHRDS40qISN1GDiNz7wPT4hHFXiFXxIU0YiwrdNXxjo0Abi9plVfdHPwMedETfGOhuMEePIIjxeVb6c34LWK43yacXIQ1CLYj2hpHwDQrFlRhULMNRdhfp8sUd9pbGtRtudGmJHJUy2OBiqazeCDVzitAS3uOgZISEKpr2zfsynZT5,UPWqh8zzrlFO9vdbBlcp2JAAjRP9iMnfqGG0DHDr0uJisSqaLkskcu6f90ADRs2zsAdxn2McA2H6xU8gkZiVsxPRJIEZVnAvWwApm87SWD1rLOxL2Ew5WIb6x4HJdAKe8jecCKU6ERfnbnfsOplyOcBfwaoIVx559IqJxtMBkubhu0l6liFKf21wKPYB49WZFoc4kPMZ54ClS0tu55q78WaDkRiJ4jnqnt9JAIeCdYjTZ5l0CBwvOxRnZVr3joJX,pRwex8ceXioHyYWJ8rrvxT0WtqYOtV4i9RGr0fUFOvzxy0Mm3dAEhLJtcVqfZBcAU8GbUvuz2XeFulLVbmlB7BTqUcWOJsyQhPdTpYSIRWh9WRHUfXsL6uuKwA0yKHtk7IuIpVe20M8pEIBR5Snjbg0DxalmplxqiW0nM6o1yGBwTTuPNNLI83zgYqoygQ7kc8wswmx4WakBB4bvXiW1C2sFwEQIbCetG1TuZreT11VkcVxrHJAxkc4jMuGtkupa,NgausAzgVfrn8PxyX8w5HqUWkq4LapAHrkNux502NQKQvtDlYvNaMXUB0SnWS4eLRJp5gYMasiBivok1CvASONsEy1OKxC8dPo7B01HPC3LJQAnc8OflNKnFjcBz2y4joLPwrN0xPIZLarFrvtHjF3rH1lXFAlQC3dCiL4pfjeJCUfoPVMRhpzdcqQCw2zancPrakOPLaEbgoN35ubOXTvfQ62IRUMc9Y6KvES539PZsMJiriizdWCvQ5CmgiWvd,KM4JpJ47OJEXMmgVYYMZXEp3W4sgQvrSGGSZ8gwBzEzzOmZ4l1afqElP0CW0ErM0orlnpiuMaslb4FVWcP3vLpwV7xdDaKOXjqMl3FpcCbmSkKRhdiCyZ6AbOZxCeHL7MietgEorzDD3G9eVrHAItX9r2lPpW5G7iev0GuOAlPNJJ7UhymV6P3KCRhUPUi2AvZvVozVx9xExb9LPagXAetucvgLlyZ9TbZb6iXYA21Al3ohI9thSAtHahJfgRCuA,QMNWYhk4mmPdKjB6b6COaFofey5Zf5V7AtqT1FacfK9QPh6pfctmghyoOyL8etRs8TfLILX2hpOd2pvJU8erwvN5Z3Rg4KYjhGxhdoYV4tMPg6yTaPlrdZYHjtMDUeHUIOKv077p8h5Q9b4D7Chqw6Bz4B8Go6ZXHfmMMG9DWjic6JJsF4lzhYEz3nc4k4Thd5W4OuRKdsxXaFCG3LmP2FvILM5EKJrFrcWo6IYpdKu3gJVD3hcYzBjvf4zGJWGp,LJ23kC99q9ME3aIZI4sapFPZttEpgd4M2LqP34NA1SGhgjAhxM0XXq4WJdtzx1FiwRo5k7YiLeNfxgqecjerWCZLlx3vr2kz1fpWdrL8vtgDtdclTA89QhRYFP4PMiSIuJAi7AMGFbZw2TYWgMZbyRC0VvRh1fWvpKDD673yT20JylOZrdAgTyXfcS3vmmpx3L0L6pNasr2M11prGrOuuvzpST90s93yrjWEtF1xkGAtjiMatc1ytEOrRtjudOdK,kkDzCZ8FbLzDvCCbjPmxRiLT9heaa5Pn8ABrLDn1vWqnoJHbM1t5Uwr0Aa7HYHDL3APAHoTyymysgY1fGh42VoLlQRjrJDgpOUnhg0mYLxzFeUYnShTjY5jtVKv9CGNmh2OmnCUXDQH5RCU7QZ6RYDvVccvO38vvHJbo2hYpMuesCcIicBekdbfuNbp5rzrHSVm8ZAz3U24kxbNT1sKHgLmWTSNa7xP2ENE50wjkegI1CNy2tSi77IZqjc1IjwWT,T5ESNm350UScvkZQp4Q12YRU7pHirynhx6TmRg8rXO1iIhX6DgF7HCPadslhjkSCkqt2oqsMXf9TEQB1Etbcb4QFZOc8eMMuU1z27GQEAvQ2vXQ0PnSm8hgXAPqD6LlU4FjJZG3bAFkemXzYzJ7XEYltTDss62JU9IGdvu1fORMTWlt6SDRwsWR9ld49AZ6E1RHqrWLanIby0YmcPhw7lVetHYmmLmh7lqOD4FNzhoHYOR1GqnKpEAg9UXCoMju94hMq6MfzDTjKtRWAMvYHrGJcwFv1I7QKF9j0vxwkQHBP2rwzRAPDPGs0bDZKqLd1rcW2QDKLel5MXa3QXLJylPcTcjtoU0hSQ5sODmZgWoVDF5huAeid8dhdV1COhEXrbmfGGCqve2wHpvH5J9bzrzutL0WLZVD3ydJFvhDOsFUpQMHmlnmXsBtwGEjAfFODa7vUpENUJO3vlTeNrf4O20WDHe5Y5RHW1vaedEA3FesuNaO9yljmEFMOB89sMYZe,4Lt5z9NoG0afQNB6EhFZrSwPTcE444aKX56L2TJNloj9a2pDOSYGMUMykBWXhar73OCKjiNT1UdpFMwuzJivqKG9DtInky0ce9HWoq59h5Hi7QNQip9XUcixx4bsCSWHlQRmZensvEerDo6sA0BSJZH8uH8r6g5xKRFAV66LOZMtFOEGFu0dP9YThdmHi54RSQpSpuftTGJwi4fk8EWb4HaeeaO6acs4xKwgI1eaHmH9RYscAcS4uGDiSc9MN55I,GZaYzlFgOGr4USJeNjAJE4jwl4oho037I6z6CAWEUp60BQOUfwP6cnR798hY4cnnbiWfulvLDt65FbasJRo1DTy1Gj8bGIH8CCvZ3JhT4gV3vEXmncE2TZP7Qzksqm1PTXcCnm0afFnQOYbdwVbxRYwpxsrmnZl3dnQ7wJl0jbo1pKOeTRnidvdrNTkS3Q7Ixj07dFr7wJG85SZvEcp3kT8PTHEr59X7OPDpebc4905ZfsMaav5HlE5CRjxxVr8l,LdfdloRLj9BUIYAavOPvWzIA5dRnvEXufOqzkLDggR1hG9rvLKABN1pYHjGVYhWf4ELbXXkDaUuYZUMgP8iuW935CbyMIEvYtp2jN5o75GqhiUVh5cihGoR4uDe48SHdeTozxNdDDlLTqdQSq3m1jlXBFPRJAVj6BrWSHZOhAmrrWAVYGSxmo6fNNu98c9WhMgj7a5G0h22uuhnEVHrOpOeQ7MgsabZzjLQlwgM25jXbD5hatVbT1gDSCCe3ksQC,XX5Z2Za5nAe8pbAgF1EUHtV55MyNBYdahXQKwKXZVT2IpZjWWgdtv1hyCf4yvEbEFw0O0HxZv31rxoQ39aULE48N48ui3dBeVZabIBPuNoXjNwpNKfWK31mwoQWxs5HGpZmPpK7u9bJWQhEC15dhwq5lbG4KIVbx2YQJqIhoLVqKKMJ6g0Ek507QRuEpxmtzxeYwMS8tabXOC8Bq2lTtyhydOfOc6U9GuJuI3K1z0EtqOVUbiMFHfQ8bCcgyQliy,S5lePcQUuz5vB3TwiePsklP3mmHLAljXG9K6r5aICYbtCPQIdHTlB7Ct8JUSOV4B56Pvbih0NUCgfFS9bUKQrPQobCoOd44sqrHG3boNwQm4H1odnacijoDzi9KW9sFF5lIe9vw7T0QTLRsqOTLMuJYJjib5TXsCsg9jy1VzvR23xwRJAAwhBf1jnA48nvVHzkriX2S83ifWG3xgEmLQ9ThDhO2pZnP5m3Zopr84THWRssHGoc3WIE8x4UclOomk,pHEMivISXFGf30IcsipUjn1vpDN6ZwVLIHvFXx3bHTUMYJchnzeCZLwKZNPrftKmJQFfUlihzsMyN0XOJzb58oGdo6MkMjUFuXZ5Q70lvJ9dHvT4OiKLPcxFi9DIbiHC7NQ42n9syjTYIonircoysW4J85ovq95EpQhdArTm7TcDBJuf2x5oLWF33ResZXvDdxwTieFUvPK2W5APovhWg6f3NDPzI4qKhaUY0vYxrWObOtFDO0M8qtUtvI9rMG3m,cp1bJggLGKrlabKNoZ93VUWRJg8zWCHPko6O91O9KWVMxExCD0M7cb800D5WVj08f46WPdvtBPHImppmPCT9H0qNSYQh8560NaW6XsPJPUfQRtmSrZznLhlZkhsxKW5ol8j8oZC6cDQt4r5YXSyWz72HbgD3HJptT7eNJKwdSpkoUdPB4xvSrkGCPjIoWaQHkk3VGdD0ZdkF50QGYbEWdCgAsKvBhRHFkhYqsxSEkD0al9vE52KrWDBCVdz1I6IN,Rmk3jXPjd0u4crzKcWCgmt5n4G96jxc2MDKz4uYFanl5kMZpd49fTMc7gx6ydROrJxOLCHF0dTUlnnRJ4aPLrSRHR9KpQQeiMIZL8uzPhRG8MNZXCnvQeOQUt9QNrmMDGkkcZY0tEqY49hPdWrP3BZ3Zcafu9dPlGuoDksmC69zaQ0asDielnd6fATF2nqed1k7KCg79HNTubLRGKN8pr3dtxWKKjZjHICn4zlF1RAxICrYAAOmc8XewaHZCHcSE,09DeiWj9gc6RMAuiCoAU2v81XhyJyLegKRkQcfkNJ2YYKijCenvsADqaFnMMSACTzUJH34IS5WoAGoVSeWLJCasMilVeIFC7TwWb1hfPWPAZug5JJfTWBwMDHZvzaw6uXm4d5qY6mLK6xAkAgTCtF1It6cQDEEDJSYtBpDhHXuJtQ5AmKkWJO4R41Qef0aKwRisHWLHg4XChcKg4H4SyRFpvP8eUkTI8QOUPvLMr9ZATI7Mjjr6kEThdxgqe7uwS,BmuACIwe7mQ7BD3d9jCsOUSEonqu4IdRTmOKpQdVcl9FdPoC4eDEdq3tResXZT1jHUuPoYGqMfGPcJDL4Q9hoaitY2uGkD5ED9V2HaQ5uTEmC3d6gFOuVRpbshzPyMJNyVFUfWrtmdMf4U8KpXh1kryQ9NusB7EgV4aROp5SgiJB7ULg4QmmfJC4PYC7jyfUA6QY9YFjrQSKLa4Cpzmv1osiqSelqZyfSLQ7Ralib3QkHsAKk1dj9Rnj68REPUOD,oAimIMjCWnEFKko7m9wUE5DZ2BGh5cQGyavfigVLFu006Y8MCxCxhIqoxAUDOCwgPs8V7hp2OGfiF7nCHDtFL4BwA1dEZ4eVGRrLA9uJHoMhQbi4va9mKOd4G7cU7NLyKsCiUGevN8cLKlrCewnDeY5QVfTU5J54MdMV3u4F5HnmWNPdUwH09xaIRX1OgOE88DQ0Ub79bbn7t8apjmRcGkjlB9V8JPdgkFlG2wnOF668lCWnewdZbzeE1v2QD8Q1,0PG3YfDIjLtkSz8gxNkqIeTl4admejAFUf998k5VYQOGX0WXn4orZ7irMHz2Hleyc4vEjTu8dnbQWMTZ4HLe5WYAoErwk6uodEXjCI2bZr6QUeBYjGnF0Zm8Z8JP0JEcqf7rauax2GqCrlYKC0USUXOowyajEQpYrmvEcL06G5dxUnQUDNuZkGM0xLmqFa9RDQNmyZG8TDxxyD0HiCy6hrdoVWn1cgUFeHpu4hChgBk0BeKHhDkLjE0NHXYTXmDv,IgTTq2qwqUaCF7PJcoftwaflyn8I7xi5MJXrx5SvTt3HgEKS2qPvwGMRK9p5cgHUKItz82m0KPztsf00lcPAi5HPBmrqOwQVDorsdHM3wXw3gfktIE2KLeUlv8EUBE0tJ2sht9zJ8huhcRaUHMQzuhnLkXzrCSdj4u69YA0jd2RxtRTZbWMiV4GrIVYBqYXfAwoF5uC7YEV5EFBMD2U1RThOFkivLziuG71yGSlLGV0quH8eLG6C2j5cXinq8jp9,Lpl5fo0v5Q2BDodDEKtcL5PQEJb1DrNy2t4h3d9kh7WLR90eqj4eNbOJls3rQoWIHriqyITG6C9SliKuAhflqWzFVOD6INz7huUCnGdynM8yKqoBLXpz1BJgGghJdoaLN9uryzX60y3pqx8EPfA7pOrpzQvsjOYm2aurHnK5D5bI8L2FBmVbxP19MgyAyn49goH38kcu6sMo7fhsxeJv2likp3F8bsaxCs6HNK5Tks40cUuQpGQPl2affCPC6Rd0,zFEg34AwZ4iBnvpF0Y6cCc6CZPSMLTFmu41oUEbt0Zd2v5iKjkR0dvDFckjwrfVOrDESusFgivl961gFaTEsp4Kx2QfKNt5Gvaa2lMyyPtLdjOfrzMarFEs9caIWz8h0k5ext706aUbe2qmLwdkIR4Cjv1NLZ3HnucfFiYvUvNiJ2eB729qnNZmvVjSza17fQLhwWvwD50sg7CaHAWpl6SHHIPI855mEHlh25hCpBTRJytH2kCfWg6mChebRTNCd,ANQp3GZiQ8PpSEJpTlgXzoidAmn9afbLhtmdy9HvmtOOjIxBSoQiNIT1UnZSmANnIjuZlv7u3IfsnzeIdoZ4LlzoN6Qp3QdAEimd1UOy7PsRAYaxMJAHhTH6fYNGNbDPNncBLG8JtGYucphMD8dk10fEqPyi9M8VyEPEJyVTjQRBZVOHyYURkcopYyAOf05ULUfFk3SZpPhtgpWMzKvBWhLdJF0w0njoIjNw7qU8LdVKnp68teAGXOnjtP85eLf2,1qfpUBHS8Q1fo30HprIZhNyEWQdaqfOww07qk641MFM5bi7LRopuUcfi9gr4FAeBw9hsrhMl7Ab0W1s1yuiezG6nzyUzdAETYYSDFl3FDajZ8P8nee0cfCMHHpCdNzHKl4XxA8aSwD8fVMWCOpJFjHQz0JG5qIbJH14ge3rbT2FEjcoKeCKZ3GrXvA5rlTwkFva4isBtNz4l3ubHOVKVk44YJqjDLwypv1Np3B5Ng8X6GCYuOKC9eYd0QTbwG6nH,tecGbTNiC07ONboTp0vomV6V2I73Pg9IIqnZaONy2jWwW6RGd3Rx2pU3dHuOMqIWf65kwQYX58kCcsADVmR4yehZ4rCPRjvbNDGDb4dIUHzomNCd5gPIGD1bBu99Ave5AQFK2Ygr2lMreqHyacCR2meQTPcjb6cedxQ5pGiOoUjzMMBNtXrxP8BvWMBJJWH36JpiyQhF1ZUECOQ9X24c9NGrPOwKVDDbtPEe79e7Rpmkd0KdYiCGTfJZf6OhAX2l,NMyBuhUQ5e5tGslUFT3ucIKmQBdxQhy9ark6TamLmOmDftR9aJdEX4C0dXTOX9seHEaZ2JfdxyA8V4LLBsEHJMvVxrnPVLEuSkBp0JACC3Y9Sajv2WJvbOJVaWpQ4CRnQdtaYyrQyHmvHLUD377b0rfdCZAH7fcezZjVhtI7Mfyo3mzpRlYGwcAVvfe3jwEIBqkXCI2Bd4Ngv3xvOcjkDwpxJKJMsnsPBLGbc5HnOBGIRLmPQW3mwz4UtGmNIBMU,LDFmqj1lDyRdfvLP3QOYTcUisVeGezaH6smwFBxhD8G90Xoutewjg9FK1aVeH5Eu6lJstWjAVESc6Uci6adYXT1pHeK8IHkMHeksUYSpNVGC8AXUH3XwEAvw6vXDtft2H2tdasRgx2QCQWXp56xJmstZn5Ye0WVgcFFaRVsnz3q9XKLA4DQfUhNQ5I06G3ikyjzUYGnwft4P66QX3ktrIco9zYF6IWnsqiq6dn1O8gPJtLvQJPy2oVuXaEUL8sir,ToUlJwprDf7XNEXWPaBsk7Lw6Oz7XX7sJOVeF0VOcl5wFSV6nNJm5iS5sXY4FyKtQw7NSAuSwRZUj5wR2pMzBPp6ZjMxpH7xwzg1nCuyLBQwi9oXHNgM6Y2suXJmx7rugX2FAU9kR5DY6uXVMNSBRs2goDYTfzLL4ggfX30Df9DVikloZXZRSwOEDR21rxYxZZElh8aZEuvPoQZ8XdL3I2Dnv18TmpKle2HLZLazdjF0S46ox6oZSMRwm6FJ0bc1,qkY2P8E3H0wu3AeizZ3GWq8UMG9gpVn4l6mkWSXcr4m4FmQTRQCIrE80rPn6eRdMupzROzp2XKGXnBiQfRw2HcKUTgL8RTsKIHGTi7hRvog0jCioW5kcyaMLJHn1AcUAeq2U352t4nMKaKPYS0q3Q4ZsYad0ftEBcGR6BGhTA0R0YjU6KotNSzVXL6z8NcGbzW3iNNb02bBch5zHklohLEOo4TppBHaWwLRVhj5TtDRSkQxCE8iVxrSMEZ6jvexr,vd77x1FkVOPzgxVB2VcROtm6iKB91iuu0ADJyCSUwIV1FnsyUa8lkuoS1u0Ms0rWZSD3720nPwl0nKjf4Dq2QjpgjqzNGITKN4EJiuFcWzpco37s88wmOJnJIMJYGjQ1ebAZBIG8ONc6y3RSbvBzOjnQV2nSrS3ZupGDDLQWs3IRC6SInIYwcTYnApzGz9HMHVSBJgQVOTppZiDOfgGODBCyyvnaAX0iA6OgH3AVeu4V4PMUWBGNS3vF9hYa0W8F,XqxFFbrNPpOhPXsGi0tdmSsFaxGRGV5AyiFs7pUk4uxM8L0Q1qGgxpMpnhhM118X2hprqr8CH8xsMXwNSs7e5yS0VXlpr4ma8phmzWtn5X4oXporrYa2KuSsqWOdHTrMBmTe4v9tSWoteccyD4evpEJa6gWs8V1bnMYtsZ57hKGzOLQAEReqnKQmTL0dlkYH4hGbIweE3qsRCGFUOzym4m9ZMps99o5Y4pljvAwvqERcjKeI38ifXWD25SSb4LbW,ZRE8aGicebMnc1tr53jzWWaLLQOOe5saSKM6Trxezdvu3BiNESCCSmlz0Vmr8SbvmafmjUMsMavaU5l5RLcSKGYvYIYCrY0bh4E23qh6i40UdwDIgC2vCr5Jr1FELiRoVIdmwie7e2pkkLeqmGIrWnQyVSvAs79YG2DNAMRlmoD3dBwntwnIe0vYRCpkmUAcj6fs7n7JGkoN0Qggeg4t7AumokdYY31AqPUUl4AoMy1sDonrjNl8tBOMP4AMFYIg,PnaNHRBnnNTlZGqGV8g3tzx8iS0xXvxNjIuJxbED5kyDVohWwDIO7bke3kndRtgumcDMUjlGDvR4atKevHOx1wiKfNbw8IMo2dGgxGNkvGRuOkL8LpfuCwD6Q85x4Uo8SCyFcqBqAW1EeILQLDQS5TCbYsW5WndFEPYsnhNaiDMpbWVOvBr57MlswcecwLOgeV9c9kQuBsy65Cos5iWgyhBlfC26dmzLTrSgOgBTKSA1I2Q9oLCXBRH3mnMwNJVj,3DKOMfV9RwvdgLmO1yleVYIcuInwvLl9luMA5Qeg2YH1bDi3rLLqbdUHIWiI6fA4JFgQPFJrEpMZ0aPflktO5KK6MeG9PfEmvU73UGgj8B45sILacd5TPEKfEUX4a6OA4OJKwkLoU6btCJeNha308tGgj8i7rImqOBl8lwRZehg257rhXDSw7rTNhR9K1MlVCMkgPZDTEvCpb4ebjjhJNdL7yv9gWoPuUA1UtNomCWvqZvDMF3yrfeNoZb2b5lcY,MeCiLRsbTwQQxVpQpbdpancfpvUkOPKsFlqJh1dl1JNq0ONpR8DRqGRUt1XOhBX8xpL04UaRNlHNf3dKigDP9P8KhsrWVvN6ITDuI5HNCmogXeyCN24gAIknrPgaLpmqo1iCE7U2t9AQQHAxyhSxjyUMTuvpgWtUzRaztXvF4HTS9foeB3wE9DVVTlT99G65ARQRFMuZ9bZGzGKrJVySCuoagMovSsuB5y4YpQnzD4yIoN9kh2ZE0J7Up8SFkTwB,doPtr0Z6kHPsaQvHsxzYBkNENyzvxYiFTouWRS3DabSnyFGUdlsQ9xlMIn4kZEmdpe3xRFtZs82aGiuYt1YM10G5SJ2hpfmSoJlZYrhUjfOHX95nTivMYgS2axAGwoCSA9qEJUGf0BfPVaVEd6AAnUDiEClaiz5jNMjMpJhkUgDcYv7j4dC9vz9ACLf9C5OXSgKj37OotHMYxd4gNT5wBCywAwbmzLWeUY0VxhfiRtb1FoPqsu7i6UD2kzpjl2RH,ZlUHDCyPaX0KSKqKrAP7ccZGkzdbEM0ufHAU7QkJg87px8oaLaSX2CUDdMXA3nHFm4KHNt3mLC8Ot7lkGgR9AE7tzmbywzlOsAYMUaYrg1j9W9kFdAA9PpMzCsHKfHI7Q7TlXrnsyJrHkdzz2dDR1dJ1kZ19uejBfCZOlhlpYzLAj2N43XJZ1rv5I58JMWhj8SJ9QuRgsu0spc0fBx8mP9zDUMkq4AoHsE719QSaoEfIO5UP2AaBkNtJW6MYq3FL,apLiiv2lxSvPKR6dwdbjXoxx5gj62ez2YT73Ao8DEoKCHFQPQOlTOMXyiQgJn15G8WZrS2GxL4xKJwsCZVrUzaTtaFpLFeED9LnNhprh8fsmWUsQrvqJGCLeQXNY4WHWSJ0k9I4KGPmqjntNGbDhuqcKtBnSAgZMpN8qEi643b26dztTKFfD1NUSK3DysHDAN1DABFnCwrj8ksnaSygVKSf4AB49dRN4zbMIlG6H6pfdAQphJxSWlqAPoo5xbGds,XLd4fL8uzkYMfTMsgir9Rn2CNQzxCaxJIkT5KlfsfLwSYHFVL76lqS1Jz6kynunFxXRfk1Khg9d3g7pculbt5yWySqgKM0vzDndst778Qst6ZrwMD3zVS5A3fXTBz8pfNYjnWKXTqJNZFQ9BwP6diU7ChejxX19iXL75XMoECvWGIUk1qX7NojJBvIJks24pMqpBwXV6xvTblVQyH4l1B6c16Xjw4zRJvS3P7anlCFXtnEFpezctREV3sC3f9j8v,iAbalOedC3vx4As7Bcegce5lkjYSIivOB3z9Lon7QPN8RcORPMfQZB3Gn8kfhJNmoJRprbvmp49JDr'
2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disco,nnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 07:40:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 07:40:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:40:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 07:40:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:40:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49684
[ThaliCore] Session.disconnect,() peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] Session.session(_:peer:didChange:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E53,6E7B86A5", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:12270C49,-5D89-4651-AC4F-E502CDB61E43
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:12270C49-5D89-4651-AC4F-E502CDB61E43
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
,# setup
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:40:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D8525647-2B71-4074-8257-C803B73ABEF2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D8525647-2B71-4074-8257-C803B73ABEF2
,2017-07-13 07:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B69838E5-3ACB-4957-AD24-2A06D0BAA49A
[ThaliCore] Browser.startList,ening
2017-07-13 07:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 07:40:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 07:40:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0)
2017-07-13 07:40:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"724A47F8-A6A9-4ACB-88A5-C246773D2521","generation":0}'
2017-07-13 07:40:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 724A47F8-A6A9-4ACB-88A5-C246773D2521, (syncValue: bzYQk4lSz7kzeiRPzxecZtxPIeP18ShV)'
2017-07-13 07:40:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] Session.init(sess,ion:identifier:connected:notConnected:) peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-13 07:40:42, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F7974F8D-9A8D-4B97-8930-80FC4382D89E","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:652433DE-F049-45A3-95C3-0B1092E6E918:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "652433DE-F049-45A3-95C3-0B1092E6E918", generation: 0)
2017-07-13 07:40:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"652433DE-F049-45A3-95C3-0B1092E6E918","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D8525647-2B71-4074-8257-C803B73ABEF2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D8525647-2B71-4074-8257-C803B73ABEF2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9717CC7E-1822-4393-B532-B06F5A7A59A4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9717CC7E-1822-4393-B532-B06F5A7A59A4", generation: 0)
,2017-07-13 07:40:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9717CC7E-1822-4393-B532-B06F5A7A59A4","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", genera,tion: 0)
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bzYQk4lSz7kzeiRPzxecZtxPIeP18ShV","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:48 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'bzYQk4lSz7kzeiRPzxecZtxPIeP18ShV', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"724A47F8-A6A9-4ACB-88A5-C246773D2521","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,07:40:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"724A47F8-A6A9-4ACB-88A5-C246773D2521","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F7974F8D-9A8D-4B97-8930-80FC4382D89E (syncValue: U8Rm4BZ9yqdrA4cbMdrEQdAXoNOZPekI)'
,2017-07-13 07:40:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", genera,tion: 0)
2017-07-13 07:40:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"U8Rm4BZ9yqdrA4cbMdrEQdAXoNOZPekI","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:53 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'U8Rm4BZ9yqdrA4cbMdrEQdAXoNOZPekI', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"F7974F8D-9A8D-4B97-8930-80FC4382D89E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13, 07:40:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F7974F8D-9A8D-4B97-8930-80FC4382D89E","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:53 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 652433DE-F049-45A3-95C3-0B1092E6E918 (syncValue: oYxzJUA,CVtH7uA32fPutm8zETeiHauoX)'
2017-07-13 07:40:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "652433DE-F049-45A3-95C3-0B1092E6E918", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "652433DE-F049-45A3-95C3-0B1092E6E918", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:652433DE-F049-45A3-95C3-0B1092E6E918:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7D196FBD-5AAD-443C-AD66-7DA180562C2B
[ThaliCore] Advertiser: session connected Peer(uuid: "D8525647-2B71-4074-8257-C803B73ABEF2", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7D196FBD-5AAD-443C-AD66-7DA180562C2B state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:652433DE-F049-45A3-95C3-0B1092E6E918:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:652433DE-F049-45A3-95C3-0B1092E6E918:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7D196FBD-5AAD-443C-AD66-7DA180562C2B
,[ThaliCore] Session.session(_:peer:didChange:) peer:652433DE-F049-45A3-95C3-0B1092E6E918:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "652433DE-F049-45A3-95C3-0B1092E6E918", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49700
,2017-07-13 07:40:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oYxzJUACVtH7uA32fPutm8zETeiHauoX","error":null,"portNumber":49700}'
,2017-07-13 07:40:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oYxzJUACVtH7uA32fPutm8zETeiHauoX', error: 'null', listeningPort: '49700''
,Connecting to the localhost:49700
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:652433DE-F049-45A3-95C3-0B1092E6E918:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7D196FBD-5AAD-443C-AD66-7DA180562C2B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:652433DE-F049-45A3-95C3-0B1092E6E918:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [2, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49700
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Client data flushed'
,Client socket error: 6146404352:error:1408F119:SSL routines:SSL3_GET_RECORD:decryption failed or bad record mac:../deps/openssl/openssl/ssl/s3_pkt.c:518:
 @native:jxcore_js_object:3:12
use@tls.js:210:8
$K@tls.js:418:8
$0.prototype.read@_stream_readable,.js:308:1
$D@tls.js:336:1
$d@_stream_writable.js:240:1
,not ok 119 Error: 6146404352:error:1408F119:SSL routines:SSL3_GET_RECORD:decryption failed or bad record mac:../deps/openssl/openssl/ssl/s3_pkt.c:518: 
,  ---
,    operator: fail
,  ...
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
,[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [2]
,# teardown
,not ok 120 got the same data back
  ---
,    operator: equal
,    expected: 'small amount of data'
,    actual:   ''
,  ...
,2017-07-13 07:40:57 - ERROR CoordinatedClient: 'unexpected result, error: 'Error: got the same data back', stack: 'assert@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js,:203:54
bound@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.strictEquals@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B696,6C5F20C6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:338:1
bound@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
shiftData/</<@/private/var/containers,/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:316:7
emit@events.js:90:1', original result: '{"id":3,"ok":false,"name":"got the same data back","operator":"equal","actual":"","expected":,"small amount of data","error":{}}''
,2017-07-13 07:40:57 - ERROR CoordinatedClient: 'test failed, name: 'Can shift data securely''
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - unknown, error: 'Error: got the same data back', stack: 'assert@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:203:54
bound@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.strictEquals@/private/var/containers/Bundle/Application/71EAEC8,6-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:338:1
bound@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
shiftData/</<@/p,rivate/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js:316:7
emit@events.js:90:1''
2017-07-13 07:40:57 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Can shift ,data securely, error: 'Error: test failed, name: 'Can shift data securely'', stack: 'CoordinatedClient.prototype._processEvent/</</endHandler/<@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/lib/Coo,rdinatedClient.js:463:22
tryCatcher@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/privat,e/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/71EAEC86-D229-4,A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/nod,e_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
,2017-07-13 07:40:57 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7D196FBD-5AAD-443C-AD66-7DA180562C2B
,[ThaliCore] Session.startOutputStream(with:) peer:7D196FBD-5AAD-443C-AD66-7DA180562C2B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [2, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-13 07:40:57 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 07:40:57 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 07:40:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-13 07:40:57 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 07:40:57 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,2017-07-13 07:40:57 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-13 07:43:51 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-13 07:43:51 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-13 07:43:51 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Error: run failed, test: 'Can shift data securely', event: 'run_Can shift data securely', sent data: '[{"uuid":"7429bd2a-7ddd-4480-9dee-bcb66c6ea3bf"},{"uuid":"ac0e4d72-52ca-4a,d2-9509-e84c7cd40172"},{"uuid":"26bb0a9c-78ae-475d-ae1e-25e4e9f16cba"}]', received data: '{"success":false}'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/ww,w/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/c,ontainers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTe,s,t.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit,@/private/var/containers/Bundle/Application/71EAEC86-D229-4A44-AC98-B6966C5F20C6/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-13 07:43:51 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
