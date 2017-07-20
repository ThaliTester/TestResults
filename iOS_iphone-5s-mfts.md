#### Test 113351851f4ec514_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7F611A76-1E9B-413B-9DE5-4623C58CBCB0/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/7F611A76-1E9B-413B-9DE5-4623C58CBCB0/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app"
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52349"
,(lldb)     command script import "/tmp/7F611A76-1E9B-413B-9DE5-4623C58CBCB0/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,2017-07-20 12:49:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:49:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:49:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:49:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:49:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:49:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:49:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "76D8A166-412E-48C0-B34E-394BD4A70A2C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:76D8A166-412E-48C0-B34E-394BD4A70A2C
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5F2B391A-880F-414B-91A8-59ECE5ED5BFD
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FFAD9338-CF63-4D08-8557-4BECDE4B5877
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A8E7B4C5-7D97-46D5-83D6-7581E377888A", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:A8E7B4C5-7D97-46D5-83D6-7581E377888A
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A8E7B4C5-7D97-46D5-83D6-7581E377888A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8E7B4C5-7D97-46D5-83D6-7581E377888A", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-20 12:49:28 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.524965941905975
,2017-07-20 12:49:28 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-07-20 12:49:28 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A8E7B4C5-7D97-46D5-83D6-7581E377888A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A8E7B4C5-7D97-46D5-83D6-7581E377888A", generation: 0)
,2017-07-20 12:49:31 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-20 12:49:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-20 12:49:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-20 12:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-20 12:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-20 12:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-20 12:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-20 12:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-20 12:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-20 12:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-20 12:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-20 12:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-20 12:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-20 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-20 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-20 12:49:35 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-20 12:49:36 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-20 12:49:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:50:02 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-20 12:50:02 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-20 12:50:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-20 12:50:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-20 12:50:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-20 12:50:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-20 12:50:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-20 12:50:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-20 12:50:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-20 12:50:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-20 12:50:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-20 12:50:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-20 12:50:32 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-20 12:50:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-20 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4BC4229D-5E86-4633-9E7A-84A11BB0E664
[ThaliCore] Browser.startListening
2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:50:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:43 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E861A072-04BF-471D-B4DB-61FE5E9F7E35
[ThaliCore] Browser.startListening
2017-07-20 12:50:47 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:50:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-20 12:50:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-2,0, 12:50:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",networkType":null}})'
2017-07-20 12:50:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:49 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "32C9683A-6F25-4393-B0FC-C14B25CD8C72", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:32C9683A-6F25-4393-B0FC-C14B25CD8C72
2017-07-20 1,2:50:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:50:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:32C9683A-6F25-4393-B0FC-C14B25CD8C72
,2017-07-20 12:50:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "250E4E5C-0FAB-4521-A1F9-8D82D6377E55", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:250E4E5C-0FAB-4521-A1F9-8D82D6377E55
2017-07-20 1,2:50:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:50:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "250E4E5C-0FAB-4521-A1F9-8D82D6377E55", generation: 1)
[ThaliCore] ,A,dvertiser.startAdvertising with peerID:250E4E5C-0FAB-4521-A1F9-8D82D6377E55
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:50:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:50:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:250E4E5C-0FAB-4521-A1F9-8D82D6377E55
,[ThaliCore] Advertiser.stopAdvertising() peerID:250E4E5C-0FAB-4521-A1F9-8D82D6377E55
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:51:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:51:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:51:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:51:00 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:51:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:51:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-20 12:51:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:51:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67
2017-07-20 12:51:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:02, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-20 12:51:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:63D2436A-3F85-4DFB-BF92-D146DC955E7F
[ThaliCore] Browser.startListening
2017-07-20 12:51:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,t,isingActive":true}'
2017-07-20 12:51:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"route,r":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A9413A1C-B780-4B25-A928-D927B5CAD186:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A9413A1C-B780-4B25-A928-D927B5CAD186", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:51:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:51:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67
,2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:51:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5BA566D9-7014-4810-A0E9-90FB098310C8
2017-07-20 1,2:51:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5D6E3E74-BB3C-4DDE-AF68-B667D4F857E7
[ThaliCore] Browser.startListening
2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:51:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
2017-07-20 12:51:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17","generation":0}'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17, (syncValue: xgHo5dskMH7pgdMqymvvrAk9iR1uthCp)'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A9413A1C-B780-4B25-A928-D927B5CAD186:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A9413A1C-B780-4B25-A928-D927B5CAD18,6", generation: 0)
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0) creat,i,ng a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A9413A1C-B780-4B25-A928-D927B5CAD186","generation":0}'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33","generation":0}'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D4BF8053-6BD4-4FAB-914E-B2038E74DE,2C","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A9413A1C-B780-4B25-A928-D927B5CAD186:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A9413A1C-B780-4B25-A928-D927B5CAD186", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C5,CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:51:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xgHo5dskMH7pgdMqymvvrAk9iR1uthCp","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 12:51:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xgHo5dskMH7pgdMqymvvrAk9iR1uthCp', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-20 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:51:08 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-20 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E1,7","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-20 12:51:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33 (syncValue: PkL5kfVkXK9lPJsNLB0a3Q53bvRnTtDh)'
,2017-07-20 12:51:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:51:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EF15780A-A250-4691-84E5-A4F6B6AACD00
[ThaliCore] Advertiser: session connected Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EF15780A-A250-4691-84E5-A4F6B6AACD00 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EF15780A-A250-4691-84E5-A4F6B6AACD00
,[ThaliCore] Session.session(_:peer:didChange:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54797
,2017-07-20 12:51:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PkL5kfVkXK9lPJsNLB0a3Q53bvRnTtDh","error":null,"portNumber":54797}'
,2017-07-20 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PkL5kfVkXK9lPJsNLB0a3Q53bvRnTtDh', error: 'null', listeningPort: '54797''
,[ThaliCore] Session.session(_:peer:didChange:) peer:EF15780A-A250-4691-84E5-A4F6B6AACD00 state: connecting -> connected
,2017-07-20 12:51:11 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-20 12:51:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:5BA566D9-7014-4810-A0E9-90FB098310C8
2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12,:,51:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54797
[ThaliCore] Session.disconnect() p,eer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EF15780A-A250-4691-84E5-A4F6B6AACD00 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:EF15780A-A250-4691-84E5-A4F6B6AACD00
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:EF15780A-A250-4691-84E5-A4F6B6AACD00
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0
2017-07-20 1,2:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:85C19076-41FD-4A0B-AAD8-535177F7E31F
[Thal,i,Core] Browser.startListening
,2017-07-20 12:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:51:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
2017-07-20 12:51:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33","generation":0}'
2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33, (syncValue: bGVeD85q9UAvgPXW4YH9gxz3STNc6uqY)'
2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5,E8A33", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found ,peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4EE9DEDB-44E6-4B7C-AC,D6-1CE24C5E8A33:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D4BF8053-6BD4-4FAB-914E-B2038E74DE2C","generation":0}'
2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:57067783-49B1-4C99-BF93-13609A1DCD30:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "57067783-49B1-4C99-BF93-13609A1DCD30", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"57067783-49B1-4C99-BF93-13609A1DCD30","generation":0}'
,2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already, running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:16 - DEBUG thaliMobileNat,iveTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2F0DF457-C0FF-4613-83CB-F1DB28937A4E","generation":0}'
,2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4E,E9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4E,E9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4E,E9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4E,E9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:4EE9DEDB,-44E6-4B7C-ACD6-1CE24C5E8A33 error: max retries exceeded
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bGVeD85q9UAvgPXW4YH9gxz3STNc6uqY","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bGVeD85q9UAvgPXW4YH9gxz3STNc6uqY', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4FE9695-DFA7-465E-8E9A-F06975202D73
[ThaliCore] Advertiser: session connected Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F4FE9695-DFA7-465E-8E9A-F06975202D73 state: notConnected -> connecting
,2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D4BF8053-6BD4-4FAB-914E-B2038E74DE2C (syncValue: ztutbGiNkzsmXDsj2ViwGaoGg1JUqCEC)'
,2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0) creating a new relay
,[ThaliCore] Session.deinit peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FFD06073-BB6B-4837-8695-D51B15694648
[ThaliCore] Advertiser: session connected Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FFD06073-BB6B-4837-8695-D51B15694648 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F4FE9695-DFA7-465E-8E9A-F06975202D73
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D4,BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4,BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ztutbGiNkzsmXDsj2ViwGaoGg1JUqCEC","error":"Peer is unavailable","portNumber":null}'
2017-07-20 12:51:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolve,d -syncValue: 'ztutbGiNkzsmXDsj2ViwGaoGg1JUqCEC', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D4BF8053-6BD4-4FAB-914E-B2038E74DE2C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D4BF8053-6BD4-4FAB-914E-B2038E74DE2C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 57067783-49B1-4C99-BF93-13609A1DCD30 (syncValue: uhwmh1yu8KVm8q4daYNDciAqWATfKDz4)'
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "57067783-49B1-4C99-BF93-13609A1DCD30", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "57067783-49B1-4C99-BF93-13609A1DCD30", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:57067783-49B1-4C99-BF93-13609A1DCD30:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FFD06073-BB6B-4837-8695-D51B15694648
,[ThaliCore] Session.session(_:peer:didChange:) peer:57067783-49B1-4C99-BF93-13609A1DCD30:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4FE9695-DFA7-465E-8E9A-F06975202D73 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:FFD06073-BB6B-4837-8695-D51B15694648 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FFD06073-BB6B-4837-8695-D51B15694648
[ThaliCore] Session.startOutputStream(with:) peer:FFD06073-BB6B-4837-8695-D51B15694648
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F4FE9695-DFA7-465E-8E9A-F06975202D73
[ThaliCore] Session.startOutputStream(with:) peer:F4FE9695-DFA7-465E-8E9A-F06975202D73
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 12:51:29 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-20 12:51:29 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-20 12:51:29 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-20 12:51:29 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 12:51:30 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-20 12:51:30 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-20 12:51:30 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-20 12:51:30 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1,
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:57067783-49B1-4C99-BF93-13609A1DCD30:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:57067783-49B1-4C99-BF93-13609A1DCD30:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "57067783-49B1-4C99-BF93-13609A1DCD30", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54807
2017-07-20 12:51:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uhwmh1yu8KVm8q4daYNDciAqWATfKDz4",,"error":null,"portNumber":54807}'
2017-07-20 12:51:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uhwmh1yu8KVm8q4daYNDciAqWATfKDz4', error: 'null', listeningPort: '54807''
,Connecting to the localhost:54807
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:57067783-49B1-4C99-BF93-13609A1DCD30:0
Connected to the localh,ost:54807
,2017-07-20 12:51:31 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-20 12:51:31 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57067783-49B1-4C99-BF93-13609A1DCD30:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:3
# teardown
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 []
,2017-07-20 12:51:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0
2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
,2017-07-20 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:57067783-49B1-4C99-BF93-13609A1DCD30
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54807
[ThaliCore] Session.disconnect() peer:57067783-49B1-4C99-BF93-13609A1DCD30:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:57067783-49B1-4C99-BF93-13609A1DCD30:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
[ThaliCore] Session.session(_:peer:didChange:) peer:F4FE9695-DFA7-465E-8E9A-F06975202D73 state: connected -> notConnected
[ThaliCore] Advert,iser: session notConnected Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.discon,nectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FFD06073-BB6B-4837-8695-D51B15694648
2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FFD06073-BB6B-4837-8695-D51B15694648 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2
2017-07-20 1,2:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76
[ThaliCore] Browser.startListening
2017-07-20 12:51:33 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:51:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
[ThaliCore] Session.deinit peer:FFD06073-BB6B-4837-8695-D51B15694648
2017-07-20 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdve,rtisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
2017-07-20 12:51:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2F0DF457-C0FF-4613-83CB-F1DB28937A4E","generation":0}'
2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2F0DF457-C0FF-4613-83CB-F1DB28937A4E, (syncValue: FjbHlur39D8jh7k0T4oP1SWizxgj4i8l)'
2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB289,37A4E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
2017-07-20 12:51:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D3868CD6-0B33-4541-B250-1BD91D759404","generation":0}'
2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:34 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
2017-07-20 12:51:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"25ACE2A0-0407-4C75-8F00-F7E349C427D2","generation":0}'
2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:34 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2F,0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2F,0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2F,0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2F,0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2F0DF457,-C0FF-4613-83CB-F1DB28937A4E error: max retries exceeded
,2017-07-20 12:51:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FjbHlur39D8jh7k0T4oP1SWizxgj4i8l","error":"Connection could not be established","portNumber":null}'
,2017-07-20 12:51:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FjbHlur39D8jh7k0T4oP1SWizxgj4i8l', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-20 12:51:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2F0DF457-C0FF-4613-83CB-F1DB28937A4E","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2F0DF457-C0FF-4613-83CB-F1DB28937A4E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-20 12:51:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D3868CD6-0B33-4541-B250-1BD91D759404 (syncValue: HOg3gXz6j0MIlRRf04UDuB2UbmCbA4Jd)'
,2017-07-20 12:51:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:51:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54823
2017-07-20 12:51:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HOg3gXz6j0MIlRRf04UDuB2UbmCbA4Jd",,"error":null,"portNumber":54823}'
2017-07-20 12:51:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HOg3gXz6j0MIlRRf04UDuB2UbmCbA4Jd', error: 'null', listeningPort: '54823''
,Connecting to the localhost:54823
,Connecting to the localhost:54823
Connecting to the localhost:54823
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] Session.startOutputStream(with:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
Connected to the localh,ost:54823
,Connected to the localhost:54823
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
Connected to the localhost:54823
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:4
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:4 [5, 6]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 96 got the same data back
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
2017-07-20 12:51:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2F0DF457-C0FF-4613-83CB-F1DB28937A4E","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:54823
[ThaliCore] Session.disconnect() peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HOg3gXz6j0MIlRRf04UDuB2UbmCbA4Jd",,"error":"Session disconnected","portNumber":null}'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D3868CD6-0B33-4541-B250-1BD91D759404","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D3868CD6-0B33-4541-B250-1BD91D759404","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
,2017-07-20 12:52:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:52:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2
,2017-07-20 12:52:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:D3868CD6-0B33-4541-B250-1BD91D759404
2017-07-20 12:52:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8BCE56E3-D4A4-471D-B13E-1983A975CB39
,2017-07-20 12:52:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:52:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C7DF29DD-99B1-49C2-8D4C-E66868816369
[ThaliCore] Browser.startListening
,2017-07-20 12:52:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:52:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:52:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
2017-07-20 12:52:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"25ACE2A0-0407-4C75-8F00-F7E349C427D2","generation":0}'
2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 25ACE2A0-0407-4C75-8F00-F7E349C427D2, (syncValue: nonQyjjpqKdtH9Mr6VM4UpNPHnqzdEPZ)'
2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
2017-07-20 12:52:01, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D3868CD6-0B33-4541-B250-1BD91D759404","generation":0}'
,2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"D60E8712-4E44-4465-9B4C-CFA9B5D222BF","generation":0}'
2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E60180BF-4B26-4B3B-897C-EC3D67F3C1BD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E60180BF-4B26-4B3B-897C-EC3D67F3C1BD", generation: 0)
2017-07-20 12:52:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E60180BF-4B26-4B3B-897C-EC3D67F3C1BD","generation":0}'
,2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:25,ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,5ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:25,ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,5ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:25,ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,5ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:25,ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:25ACE2A0,-0407-4C75-8F00-F7E349C427D2 error: max retries exceeded
2017-07-20 12:52:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nonQyjjpqKdtH9Mr6VM4UpNPHnqzdEPZ","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 12:52:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nonQyjjpqKdtH9Mr6VM4UpNPHnqzdEPZ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 12:52:12 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"25ACE2A0-0407-4C75-8F00-F7E349C427D2","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:52:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 12:52:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"25ACE2A0-0407-4C75-8F00-F7E349C427D2","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 12:52:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 12:52:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D60E8712-4E44-4465-9B4C-CFA9B5D222BF (syncValue: 5KPBO9K,ay9GsLT6TlkYR57Le1JegKq36)'
2017-07-20 12:52:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D60E8712-4E44,-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CD87EB12-FC20-4C30-9FFB-B5E6F77EFA53
[ThaliCore] Advertiser: session connected Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CD87EB12-FC20-4C30-9FFB-B5E6F77EFA53 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CD87EB12-FC20-4C30-9FFB-B5E6F77EFA53
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD87EB12-FC20-4C30-9FFB-B5E6F77EFA53 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CD87EB12-FC20-4C30-9FFB-B5E6F77EFA53
[ThaliCore] Session.startOutputStream(with:) peer:CD87EB12-FC20-4C30-9FFB-B5E6F77EFA53
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-20 12:52:15 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-20 12:52:15 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-20 12:52:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-20 12:52:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-20 12:52:16 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [5, 6]
,[ThaliCore] Session.session(_:peer:didChange:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54842
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5KPBO9Kay9GsLT6TlkYR57Le1JegKq36","error":null,"portNumber":54842}'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5KPBO9Kay9GsLT6TlkYR57Le1JegKq36', error: 'null', listeningPort: '54842''
,Connecting to the localhost:54842
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [5, 6, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:54842
,2017-07-20 12:52:16 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-20 12:52:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [5, 6]
,2017-07-20 12:52:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:52:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8BCE56E3-D4A4-471D-B13E-1983A975CB39
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54842
[ThaliCore] Session.disconnect() p,eer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD87EB12-FC20-4C30-9FFB-B5E6F77EFA53 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:CD87EB12-FC20-4C30-9FFB-B5E6F77EFA53
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:CD87EB12-FC20-4C30-9FFB-B5E6F77EFA53
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7099301E-F445-486E-A603-9612A1AC58CE
,2017-07-20 12:52:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FFEC3634-E867-44F8-975F-DF9D3432CC9D
[ThaliCore] Browser.startListening
,2017-07-20 12:52:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:52:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-20 12:52:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
2017-07-20 12:52:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D60E8712-4E44-4465-9B4C-CFA9B5D222BF","generation":0}'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D60E8712-4E44-4465-9B4C-CFA9B5D222BF, (syncValue: knGz1143FJUnBwUqh6tqmAUumhgB8JyN)'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D,222BF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) fou,nd peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
2017-07-20 12:52:18, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B4121540-BB03-4856-A0E5-C0E220AE5A98","generation":0}'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:18 - DEBUG, thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FC588A3-45D2-4DE6-BDAE-579C029A9613:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FC588A3-45D2-4DE6-BDAE-579C029A9613", generation: 0)
,2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1FC588A3-45D2-4DE6-BDAE-579C029A9613","generation":0}'
,2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7099301E-F445-486E-A603-9612A1AC58CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D6,0E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D6,0E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D6,0E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:96A5EA25-D33D-46D7-95E3-0E23D1C7D430
[ThaliCore] Advertiser: session connected Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:96A5EA25-D33D-46D7-95E3-0E23D1C7D430 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D6,0E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:D60E8712,-4E44-4465-9B4C-CFA9B5D222BF error: max retries exceeded
2017-07-20 12:52:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"knGz1143FJUnBwUqh6tqmAUumhgB8JyN","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 12:52:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'knGz1143FJUnBwUqh6tqmAUumhgB8JyN', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 12:52:29 - DEBUG thaliMobileNativeWrapper: 'Received ,peer availability changed event with {"peerIdentifier":"D60E8712-4E44-4465-9B4C-CFA9B5D222BF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:52:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 12:52:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D60E8712-4E44-4465-9B4C-CFA9B5D222BF","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 12:52:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 12:52:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B4121540-BB03-4856-A0E5-C0E220AE5A98 (syncValue: c45hBZB93Za0JLPko9HnwlVWi4g2caZZ)'
2017-07-20 12:52:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4121540-BB03,-4856-A0E5-C0E220AE5A98:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 12:52:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
2017-07-20 12:52:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:96A5EA25-D33D-46D7-95E3-0E23D1C7D430
,[ThaliCore] Session.session(_:peer:didChange:) peer:96A5EA25-D33D-46D7-95E3-0E23D1C7D430 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96A5EA25-D33D-46D7-95E3-0E23D1C7D430
[ThaliCore] Session.startOutputStream(with:) peer:96A5EA25-D33D-46D7-95E3-0E23D1C7D430
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [5, 6, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (4522 bytes):'
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
[ThaliCore] Session.session(_:peer:didChange:) peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uu,id: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54859
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 12:52:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"c45hBZB93Za0JLPko9HnwlVWi4g2caZZ","error":null,"portNumber":54859}'
,2017-07-20 12:52:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'c45hBZB93Za0JLPko9HnwlVWi4g2caZZ', error: 'null', listeningPort: '54859''
,Connecting to the localhost:54859
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
Connected to the localhost:54859
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [5, 6, 9, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (44731 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
,[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [5, 6, 9]
,ok 102 got the same data back
,# teardown
,2017-07-20 12:52:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:52:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 12:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7099301E-F445-486E-A603-9612A1AC58CE
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B4121540-BB03-4856-A0E5-C0E220AE5A98
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54859
[ThaliCore] Session.disconnect() p,eer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:96A5EA25-D33D-46D7-95E3-0E23D1C7D430 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:96A5EA25-D33D-46D7-95E3-0E23D1C7D430
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:96A5EA25-D33D-46D7-95E3-0E23D1C7D430
[ThaliCore] Session.deinit peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
[ThaliCore] BrowserRelay.deinit
2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCha,nged registered to native'
2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:52:33 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A95FB2DF-4417-48B9-9F59-621A1F56F1DA
[ThaliCore] Browser.startListening
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:668195C4-AF2F-4CED-8392-5A206791E4AB
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D60E8712-4E44-4465-9B4C-CFA9B5D222BF","generation":0}]'
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D60E8712-4E44-4465-9B4C-CFA9B5D222BF","generation":0}'
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7114A0C4-6ABB-4EFC-9D9D-3A41FEDA2B71:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7114A0C4-6ABB-4EFC-9D9D-3A41FEDA2B71", generation: 0)
2017-07-20 12:52:34 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7114A0C4-6ABB-4EFC-9D9D-3A41FEDA2B71","generation":0}]'
2017-07-20 12:52:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7114A0C4-6ABB-4EFC-9D9D-3A41FEDA2B71","generation":0}'
2017-07-20 12:52:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:668195C4-AF2F-4CED-8392-5A206791E4AB
2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-20 12:52:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:605E7383-58C5-4CC6-9620-A58547BF57F8
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FAD1BCA8-AF5F-470A-993B-936DF4A08F63", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FAD1BCA8-AF5F-470A-993B-936DF4A08F63
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:FAD1BCA8-AF5F-470A-993B-936DF4A08F63
,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-20 12:52:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-20 12:52:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-20 12:52:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-20 12:52:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-20 12:52:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-20 12:52:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-20 12:52:42 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:17fa82f7-9b7e-4ca9-b2e6-70c55650ece6 error: startListeningNotActive
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"bL8ayAxESsX5Q9GeprsJ0WCSvs9EIkCo","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
,ok 130 listeningPort is null
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"17fa82f7-9b7e-4ca9-b2e6-70c55650ece6","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"17fa82f7-9b7e-4ca9-b2e6-70c55650ece6","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:171BA0C7-E08D-4EE9-B7DD-A69163106836
,[ThaliCore] Browser.startListening
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
,ok 132 Got null as expected
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uS9rEXHVWdZRt4aVHxvxg6Y9ontI5N4D","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-20 12:52:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9602BD6B-8CAE-45FE-9903-74B9CACDFDFB
[ThaliCore] Browser.startListening
2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:52:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on star,ting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:45 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:ea9e47a0-14aa-491b-8924-69b275614b8d
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:46 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7EACCE85-5177-40E5-B094-99AE50B25DB4
2017-07-20 1,2:52:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0E1F30A8-C3B2-42BD-9077-9FCEA13A0A19
[Tha,l,iCore] Browser.startListening
2017-07-20 12:52:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:52:47 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:52:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
,2017-07-20 12:52:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D60E8712-4E44-4465-9B4C-CFA9B5D222BF","generation":0}'
,2017-07-20 12:52:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D60E8712-4E44-4465-9B4C-CFA9B5D222BF (syncValue: A8ujKaodNG2dv1mc1ivNP91w2eV70kLd)'
,2017-07-20 12:52:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
2017-07-20 12:52:48 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9749BEAA-3E3A-45D7-9075-645C99E7D51C","generation":0}'
2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69525797-BA3F-4E13-AF0F-E86172E8CB6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69525797-BA3F-4E13-AF0F-E86172E8CB6E", generation: 0)
,2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"69525797-BA3F-4E13-AF0F-E86172E8CB6E","generation":0}'
,2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D6,0E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:52:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"A8ujKaodNG2dv1mc1ivNP91w2eV70kLd","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 12:52:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'A8ujKaodNG2dv1mc1ivNP91w2eV70kLd', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 12:52:50 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"D60E8712-4E44-4465-9B4C-CFA9B5D222BF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:52:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 12:52:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D60E8712-4E44-4465-9B4C-CFA9B5D222BF","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-20 12:52:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:50 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 12:52:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9749BEAA-3E3A-45D7-9075-645C99E7D51C (syncValue: uU0ekukqKCPIu4yXtoGIhCu,qluXPzkpz)'
2017-07-20 12:52:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9749BEAA-3E3A-45D7-9075-645C9,9E7D51C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:52:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54869
2017-07-20 12:52:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uU0ekukqKCPIu4yXtoGIhCuqluXPzkpz",,"error":null,"portNumber":54869}'
2017-07-20 12:52:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uU0ekukqKCPIu4yXtoGIhCuqluXPzkpz', error: 'null', listeningPort: '54869''
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket,:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0) found active relay
,2017-07-20 12:52:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"f349tF3lbrRCe07EQWZuMPGKgETTjMCI","error":null,"portNumber":54869}'
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9749BEAA-3E3A-45D7-9075-645C99,E7D51C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [5, 6, 9, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0) found active relay
,2017-07-20 12:52:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZhohitahiHRV5GfyZkpxpH2vMbeMwqd5","error":null,"portNumber":54869}'
ok 147 No error
ok 148 Ports equal
,# teardown
,2017-07-20 12:52:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:7EACCE85-5177-40E5-B094-99AE50B25DB4
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12,:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54869
[ThaliCore] VirtualSocket.closeStr,eams() vsID:11
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:11 [5, 6, 9]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
,[ThaliCore] Session.deinit peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-20 12:52:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-20 12:53:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-20 12:53:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-20 12:53:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-20 12:53:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-20 12:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'listening 54872'
ok 149 Should throw
,# teardown
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'listening 54874'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'listening 54877'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:04 - DEBUG createNativeListener: 'listening 54881'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-20 12:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:04 - DEBUG createNativeListener: 'listening 54886'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'listening 54890'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'listening 54894'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'listening 54898'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'listening 54902'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-20 12:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-20 12:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:07 - DEBUG createNativeListener: 'listening 54954'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-20 12:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'listening 54958'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:08 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-20 12:53:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:08 - DEBUG createNativeListener: 'listening 54961'
ok 196 port must be in range
,# teardown
,2017-07-20 12:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:09 - DEBUG createNativeListener: 'listening 54962'
ok 197 second start should return same port
,# teardown
,2017-07-20 12:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'listening 54964'
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-20 12:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-20 12:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-20 12:53:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-20 12:53:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-20 12:53:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 54966
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EA32759D-73B0-4139-BC54-9CBBA9318A85
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42EF0320-C77A-4BB7-BF53-E9CA3636A170
,[ThaliCore] Browser.startListening
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:53:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9749BEAA-3E3A-45D7-9075-645C99E7D51C","generation":0}'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9749BEAA-3E3A-45D7-9075-645C99E7D51C (syncValue: WDwB7edNOM7VzS7jTnAsLJJaqVLbdSs3)'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E6222F0B-BC09-4C60-88EE-3F2C1C1244C7","generation":0}'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"35100B8F-5608-4D74-85AC-379CF9FF5614","generation":0}'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,49BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,49BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:53:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WDwB7edNOM7VzS7jTnAsLJJaqVLbdSs3","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 12:53:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WDwB7edNOM7VzS7jTnAsLJJaqVLbdSs3', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 12:53:16 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"9749BEAA-3E3A-45D7-9075-645C99E7D51C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:53:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 12:53:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9749BEAA-3E3A-45D7-9075-645C99E7D51C","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-20 12:53:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:53:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 12:53:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E6222F0B-BC09-4C60-88EE-3F2C1C1244C7 (syncValue: 3HsGwILcnPTndh2o7RZqrQm,q90WKEKIR)'
2017-07-20 12:53:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E6222F0B-BC09-4C60-88EE-3F2C1,C1244C7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:53:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54976
2017-07-20 12:53:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3HsGwILcnPTndh2o7RZqrQmq90WKEKIR",,"error":null,"portNumber":54976}'
2017-07-20 12:53:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3HsGwILcnPTndh2o7RZqrQmq90WKEKIR', error: 'null', listeningPort: '54976''
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617
[ThaliCore] Advertiser: session connected Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617 state: notConnected -> connecting
,ok 210 should be equal
2017-07-20 12:53:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 35100B8F-5608-4D74-85AC-379CF9FF5614 (syncValue: ePoeAqtkPqvjXSqMiv9RPHQldlxMOOtQ)'
2017-07-20 12:53:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:13134C84-C172-40B2-A179-A5442E4B59D5
[ThaliCore] Advertiser: session connected Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:13134C84-C172-40B2-A179-A5442E4B59D5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54980
,2017-07-20 12:53:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ePoeAqtkPqvjXSqMiv9RPHQldlxMOOtQ","error":null,"portNumber":54980}'
,2017-07-20 12:53:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ePoeAqtkPqvjXSqMiv9RPHQldlxMOOtQ', error: 'null', listeningPort: '54980''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:13134C84-C172-40B2-A179-A5442E4B59D5
,[ThaliCore] Session.session(_:peer:didChange:) peer:13134C84-C172-40B2-A179-A5442E4B59D5 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EA32759D-73B0-4139-BC54-9CBBA9318A85
2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7,
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54976
[ThaliCore] Session.disconnect() peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13134C84-C172-40B2-A179-A5442E4B59D5 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:13134C84-C172-40B2-A179-A5442E4B59D5
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:35100B8F-5608-4D74-85AC-379CF9FF5614
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54980
[ThaliCore] Session.disconnect() p,eer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617 state,: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] Session.deinit peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] Session.deinit peer:13134C84-C172-40B2-A179-A5442E4B59D5
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:53:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 54982
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:53:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20, 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D1F70EEB-FC68-4F13-8138-43E08E22C687
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A0F9F4E1-39FE-4678-A72A-5F221C9E91B6
[ThaliCore] Browser.startList,ening
2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:53:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-20 12:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"35100B8F-5608-4D74-85AC-379CF9FF5614","generation":0}'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 35100B8F-5608-4D74-85AC-379CF9FF5614 (syncValue: cr3A1zRoGLrwH5TnFfgxRNKLT5UkAhOm)'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88535592-00DC-406A-B6E1-682309662B75:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"88535592-00DC-406A-B6E1-682309662B75","generation":0}'
2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}'
2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:35,100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,5100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:53:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cr3A1zRoGLrwH5TnFfgxRNKLT5UkAhOm","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 12:53:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cr3A1zRoGLrwH5TnFfgxRNKLT5UkAhOm', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 12:53:32 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"35100B8F-5608-4D74-85AC-379CF9FF5614","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:53:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 12:53:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"35100B8F-5608-4D74-85AC-379CF9FF5614","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-20 12:53:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:53:32 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 12:53:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 88535592-00DC-406A-B6E1-682309662B75 (syncValue: 8zCffxY9JdJ2bah5m5vkD7B,T5nKHDJz5)'
2017-07-20 12:53:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:88535592-00DC-406A-B6E1-68230,9662B75:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:53:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:88535592-00DC-406A-B6E1-682309662B75:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:88535592-00DC-406A-B6E1-682309662B75:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:88535592-00DC-406A-B6E1-682309662B75:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54993
2017-07-20 12:53:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8zCffxY9JdJ2bah5m5vkD7BT5nKHDJz5",,"error":null,"portNumber":54993}'
2017-07-20 12:53:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8zCffxY9JdJ2bah5m5vkD7BT5nKHDJz5', error: 'null', listeningPort: '54993''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-20 12:53:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2AD1575A-57BF-49EF-A14E-3BCF4FE28514 (syncValue: TkBpj1jQ4xJ3Ejh1XyKvOkD2alkw1p4x)'
,2017-07-20 12:53:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE
[ThaliCore] Advertiser: session connected Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C78FA2B1-F11B-457E-BD91-68723D2A2024
[ThaliCore] Advertiser: session connected Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C78FA2B1-F11B-457E-BD91-68723D2A2024 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54999
2017-07-20 12:53:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TkBpj1jQ4xJ3Ejh1XyKvOkD2alkw1p4x","error":null,"portN,umber":54999}'
2017-07-20 12:53:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TkBpj1jQ4xJ3Ejh1XyKvOkD2alkw1p4x', error: 'null', listeningPort: '54999''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C78FA2B1-F11B-457E-BD91-68723D2A2024
,[ThaliCore] Session.session(_:peer:didChange:) peer:C78FA2B1-F11B-457E-BD91-68723D2A2024 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:53:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D1F70EEB-FC68-4F13-8138-43E08E22C687
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:88535592-00DC-406A-B6E1-682309662B75
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54993
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:88535592-00DC-406A-B6E1-682309662B75:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:88535592-00DC-406A-B6E1-682309662B75:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54999
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C78FA2B1-F11B-457E-BD91-68723D2A2024 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C78FA2B1-F11B-457E-BD91-68723D2A2024
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:53:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8zCffxY9JdJ2bah5m5vkD7BT5nKHDJz5","error":"Session disconnected","portNumber":null}'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"88535592-00DC-406A-B6E1-682309662B75","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"88535592-00DC-406A-B6E1-682309662B75","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:C78FA2B1-F11B-457E-BD91-68723D2A2024
,[ThaliCore] Session.deinit peer:88535592-00DC-406A-B6E1-682309662B75:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:46 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'listening 55003'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'listening 55004'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B3F5BFE8-06A9-4277-A132-11D2B950CDB3
[ThaliCore] Browser.st,artListening
2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'listening 55005'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C190E04A-1A3C-46C5-B482-2DDF74BDA201", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:C190E04A-1A3C-46C5-B482-2DDF74BDA201
2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:47 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C190E04A-1A3C-46C5-B482-2DDF74BDA201", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:C190E04A-1A3C-46C5-B482-2DDF74BDA201
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C190E04A-1A3C-46C5-B482-2DDF74BDA201
[ThaliCore] Advertiser.stopAdvertising() peerID:C190E04A-1A3C-46C5-B482-2DDF74BDA201
2017-07-20 12:53:48 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,2017-07-20 12:53:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'listening 55008'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:50 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-20 12:53:50 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 241 specific error expected
,# teardown
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:53:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'listening 55009'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D597641B-AB8B-47CC-A729-169EAA1215BC
,[ThaliCore] Browser.startListening
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8DE8093E-06C0-4872-9D49-C26276EA23FA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8DE8093E-06C0-4872-9D49-C26276EA23FA
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:8DE8093E-06C0-4872-9D49-C26276EA23FA
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'listening 55012'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B027396B-ED91-492F-B8AD-C85EA087A6EF
,[ThaliCore] Browser.startListening
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C3819C4B-89CB-4372-ACB8-71DE648B0D3B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C3819C4B-89CB-4372-ACB8-71DE648B0D3B
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C3819C4B-89CB-4372-ACB8-71DE648B0D3B
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'listening 55014'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8DCDFE25-8915-457B-A021-C9E5A8FB0E7F
[ThaliCore] Browser.startListening
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:53:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "83765E14-9A80-49BE-83D1-8915F462973C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:83765E14-9A80-49BE-83D1-8915F462973C
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
2017-07-20 12:53:52 - DEBUG t,haliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:53:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"st,arted":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:83765E14-9A80-49BE-83D1-8915F462973C
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:53:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}]'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-20 12:53:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:52 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:53 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-20 12:53:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:53 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:54 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:54 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-20 12:53:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:55 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-20 12:53:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-20 12:53:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-20 12:53:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-20 12:53:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-20 12:53:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-20 12:53:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-20 12:53:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'listening 55017'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B012DF81-9018-4856-8127-005CF1DC47C3
[ThaliCore] Browser.st,artListening
2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:53:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:53:58 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-20 12:53:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'listening 55018'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "294FBFE5-313A-4275-B958-DEC9712FDC3C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:294FBFE5-313A-4275-B958-DEC9712FDC3C
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:294FBFE5-313A-4275-B958-DEC9712FDC3C
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"adver,tisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'listening 55020'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'listening 55021'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:45ABDFDC-BC5F-4742-BAD4-8A1F4CEA63AF
,[ThaliCore] Browser.startListening
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
2017-07-20 12:53:59 - INFO th,aliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BF46FCDF-DE40-4282-B85D-9C228B9B54D0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BF46FCDF-DE40-4282-B85D-9C228B9B54D0
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:53:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}]'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:53:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 277 portNumber equal null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BF46FCDF-DE40-4282-B85D-9C228B9B54D0
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-20 12:54:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-20 12:54:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:00 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-20 12:54:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-20 12:54:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-20 12:54:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:02 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'listening 55023'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:85F39250-2FED-41F9-B0C4-DCB5E27F5FD1
,[ThaliCore] Browser.startListening
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:22488835-A637-4241-BF70-B8FAAEA6FBCB
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:54:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADB21495-5A54-49DC-88F8-51FC343DC59F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADB21495-5A54-49DC-88F8-51FC343DC59F", generation: 0)
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","generation":0}]'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","generation":0}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:54:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ADB21495-5A54-49DC-88F8-51FC343DC59F (syncValue: H8SlUzgmcMJKxQRy8fhuqcVGL5eEOXER)'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ADB21495-5A54-49DC-88F8-51FC343DC59F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADB21495-5A54-49DC-88F8-51FC343DC59F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ADB21495-5A54-49DC-88F8-51FC343DC59F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7054CC02-4F35-4202-9635-D1C4F6D139FE
[ThaliCore] Advertiser: session connected Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7054CC02-4F35-4202-9635-D1C4F6D139FE state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:236824DA-F1E1-4D80-B7AF-2C19AE7BC695:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "236824DA-F1E1-4D80-B7AF-2C19AE7BC695", generation: 0)
2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","generation":0}]'
2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","generation":0}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 12:54:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADB21495-5A54-49DC-88F8-51FC343DC59F:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ADB21495-5A54-49DC-88F8-51FC343DC59F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADB21495-5A54-49DC-88F8-51FC343DC59F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ADB21495-5A54-49DC-88F8-51FC343DC59F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55026
,2017-07-20 12:54:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"H8SlUzgmcMJKxQRy8fhuqcVGL5eEOXER","error":null,"portNumber":55026}'
,2017-07-20 12:54:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'H8SlUzgmcMJKxQRy8fhuqcVGL5eEOXER', error: 'null', listeningPort: '55026''
,2017-07-20 12:54:05 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:ADB21495-5A54-49DC-88F8-51FC343DC59F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ADB21495-5A54-49DC-88F8-51FC343DC59F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [5, 6, 9, 12]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7054CC02-4F35-4202-9635-D1C4F6D139FE
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:173A8E1A-8B33-4704-86E4-A6BCD393D858
[ThaliCore] Advertiser: session connected Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:173A8E1A-8B33-4704-86E4-A6BCD393D858 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7054CC02-4F35-4202-9635-D1C4F6D139FE state: connecting -> connected
,2017-07-20 12:54:06 - DEBUG testUtils: 'Got response data'
,2017-07-20 12:54:06 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7054CC02-4F35-4202-9635-D1C4F6D139FE
[ThaliCore] Session.startOutputStream(with:) peer:7054CC02-4F35-4202-9635-D1C4F6D139FE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [5, 6, 9, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:173A8E1A-8B33-4704-86E4-A6BCD393D858
,[ThaliCore] Session.session(_:peer:didChange:) peer:173A8E1A-8B33-4704-86E4-A6BCD393D858 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:173A8E1A-8B33-4704-86E4-A6BCD393D858
[ThaliCore] Session.startOutputStream(with:) peer:173A8E1A-8B33-4704-86E4-A6BCD393D858
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [5, 6, 9, 12, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[Thali,Core] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [5, 6, 9, 13, 14]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [5, 6, 9, 13]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) ,client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:173A8E1A-8B33-4704-86E4-A6BCD393D858 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:173A8E1A-8B33-4704-86E4-A6BCD393D858
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:22488835-A637-4241-BF70-B8FAAEA6FBCB
,2017-07-20 12:54:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 12:54:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:54:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:54:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:ADB21495-5A54-49DC-88F8-51FC343DC59F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55026
[ThaliCore] Session.disconnect() peer:ADB21495-5A54-49DC-88F8-51FC343DC59F:0
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Sock,et closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual sock,et vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [5, 6, 9]
,[ThaliCore] Session.session(_:peer:didChange:) peer:7054CC02-4F35-4202-9635-D1C4F6D139FE state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
,[ThaliCore] Session.deinit peer:173A8E1A-8B33-4704-86E4-A6BCD393D858
[ThaliCore] Session.deinit peer:ADB21495-5A54-49DC-88F8-51FC343DC59F:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:54:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-20 12:54:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-20 12:54:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:54:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:54:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-20 12:54:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 12:54:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 12:54:12 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'listening 55030'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:13 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
,ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'listening 55031'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D054692E-0FDF-483C-9C37-06DF1481C457
[ThaliCore] Browser.st,artListening
2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
,ok 309 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:54:14 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-20 12:54:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateU,pdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advert,isingActive":false}'
2017-07-20 12:54:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'listening 55032'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "581A6FC7-FC66-486F-B899-5143A4F1D9B5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:581A6FC7-FC66-486F-B899-5143A4F1D9B5
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "581A6FC7-FC66-486F-B899-5143A4F1D9B5", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:581A6FC7-FC66-486F-B899-5143A4F1D9B5
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 315 error should be null
,ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:581A6FC7-FC66-486F-B899-5143A4F1D9B5
,[ThaliCore] Advertiser.stopAdvertising() peerID:581A6FC7-FC66-486F-B899-5143A4F1D9B5
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'listening 55035'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:54:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
,ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-20 12:54:15 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
ok 328 native router should be bad
,# teardown
,ok 329 error should be null
ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'listening 55036'
,ok 332 first call should succeed
,ok 333 first call should succeed
,ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
,ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-20 12:54:16 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
,ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-20 12:54:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-20 12:54:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6247e285-bc91-4c98-ac81-d49404ffde14","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 344 should be called once
,ok 345 should not have been called more than once
,# teardown
,2017-07-20 12:54:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6247e285-bc91-4c98-ac81-d49404ffde14","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 346 error should be null
ok 347 error should be null
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
2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c5cbe953-3a83-4229-819b-ccb2a470ced6","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 354 peer should be available
ok 355 cache contains native peer
2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c5cbe953-3a83-4229-819b-ccb2a470ced6","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 356 peer should be unavailable
,ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26dd2f3b-19c1-46c8-9887-b22d7f36dbfd","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 362 peer should be available
ok 363 cache contains wifi peer
2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26dd2f3b-19c1-46c8-9887-b22d7f36dbfd","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 364 peer should be unavailable
ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2a0320c8-6c2f-41b9-9dc2-40817b5b0b7b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 369 first peer is a,vailable
2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ea10fda8-b80d-46d7-97d0-fff1df6430b3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 370 second, peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2a0320c8-6c2f-41b9-9dc2-40817b5b0b7b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ea10fda8-b80d-46d7-97d0-fff1df6430b3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
,ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a7c95d7e-6e96-4c89-877c-0a4f62818fd6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 376 peer is available
,# teardown
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a7c95d7e-6e96-4c89-877c-0a4f62818fd6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-20 12:54:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-20 12:54:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"07a4d820-520a-4d35-8b95-e3970324972d","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be ,available
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"07a4d820-520a-4d35-8b95-e3970324972d","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be ,available
,ok 388 should store correct generation
,# teardown
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"07a4d820-520a-4d35-8b95-e3970324972d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
,ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'listening 55037'
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4a9d8c66-aa00-4bda-8eb6-ece78a648f5e","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4a9d8c66-aa00-4bda-8eb6-ece78a648f5e","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,# teardown
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4a9d8c66-aa00-4bda-8eb6-ece78a648f5e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:19 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-20 12:54:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'listening 55038'
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f1e00504-bfb0-4cdd-9f5f-df7b480d95ef","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 399 discovered available peer
,ok 400 peer is available
,# teardown
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f1e00504-bfb0-4cdd-9f5f-df7b480d95ef","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
,ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d8884acb-b3b0-444a-ba7c-95bed19682b2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 404 peer should be available
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d8884acb-b3b0-444a-ba7c-95bed19682b2","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 405 peer should be unavailable
,ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
,ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 55039'
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3a6c8925-41e3-4aab-888d-1eb84d4ce7c9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 410 first peer is expected to be available
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"30845f20-9ca8-4e84-87c3-e4b33bdb69c7","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 411 second peer is expected to be available
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"30845f20-9ca8-4e84-87c3-e4b33bdb69c7","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 412 peer became unavailable
,ok 413 it was wifi peer
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"30845f20-9ca8-4e84-87c3-e4b33bdb69c7","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"30845f20-9ca8-4e84-87c3-e4b33bdb69c7","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3a6c8925-41e3-4aab-888d-1eb84d4ce7c9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-20 12:54:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
,ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 55040'
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a3adf56a-4e85-47b6-a2e5-20ce71b36296","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 424 first peer is expected to be available
,2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8a6af689-7a89-4303-a312-96f9d640388b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 425 second peer is expected to be available
,2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a3adf56a-4e85-47b6-a2e5-20ce71b36296","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8a6af689-7a89-4303-a312-96f9d640388b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:21 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-20 12:54:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
,ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-20 12:54:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
,ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f295cac9-9546-44b3-88bd-2797e68ca53f","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 437 peer discovered ,first time does not have new address
2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f295cac9-9546-44b3-88bd-2797e68ca53f","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 438 address has not been changed
2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f295cac9-9546-44b3-88bd-2797e68ca53f","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 439 new port handled correctly
,2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f295cac9-9546-44b3-88bd-2797e68ca53f","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 440 new host handled, correctly
2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f295cac9-9546-44b3-88bd-2797e68ca53f","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 441 new,AddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
,ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-20 12:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
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
,2017-07-20 12:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 452 error should be null
ok 453 error should be null
,# setup
,ok 454 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 455 should be equal
,# teardown
,ok 456 error should be null
,ok 457 error should be null
,# setup
,ok 458 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-20 12:54:23 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
,ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-20 12:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 contains expected properties
,ok 463 the same hostAddress
,ok 464 the same portNumber
,# teardown
,2017-07-20 12:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
,ok 469 the same hostAddress
,ok 470 the same portNumber
,# teardown
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'listening 55041'
2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e0a2819b-421c-4c52-9603-e051e4e4ff2b","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 474 Got specific error message
,# teardown
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e0a2819b-421c-4c52-9603-e051e4e4ff2b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'listening 55042'
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4a62756b-3904-4b0b-9930-e4b34a406da4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:4a62756b-3904-4b0b-9930-e4b34a406da4
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4a62756b-3904-4b0b-9930-e4b34a406da4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-20 12:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-20 12:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
,ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-20 12:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
,ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'listening 55043'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4A4A1603-F530-4993-8D7C-5B1FED41E696
,[ThaliCore] Browser.startListening
,2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e53e6768-08bf-4481-a670-47ff5dd57590","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c42daf30-d90c-4bd3-b167-9bf1a38cd563","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e53e6768-08bf-4481-a670-47ff5dd57590","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c42daf30-d90c-4bd3-b167-9bf1a38cd563","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-20 12:54:27 - DEBUG thaliMobileNativeWrapper: 'listening 55044'
,2017-07-20 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c4760c91-0818-4b43-920f-be7aa5c87b8e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 1
,ok 513 2
,2017-07-20 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2d7d9b68-4500-4cf4-9b1f-a6cc41257c36","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-20 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c4760c91-0818-4b43-920f-be7aa5c87b8e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2d7d9b68-4500-4cf4-9b1f-a6cc41257c36","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
,ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-20 12:54:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-20 12:54:28 - DEBUG thaliMobileNativeWrapper: 'listening 55045'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "56CC6A57-6C82-4856-8C19-30,E36C8EC7B7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:56CC6A57-6C82-4856-8C19-30E36C8EC7B7
2017-07-20 12:54:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 522 error should be null
ok 523 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2
[ThaliCore] Browser.startListening
,2017-07-20 12:54:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
2017-07-20 12:54:29 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","generation":0}]'
2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","generation":0}'
,2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 12:54:29 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 0C355728-450D-4AE9-898C-AC65C78ACABC (syncValue: 0)'
2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C,:0
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid,: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90045F83-13E2-42E6-8B7E-9138CCA74D8C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0C355728,-450D-4AE9-898C-AC65C78ACABC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvai,labilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"90045F83-13E2-42E6-8B7E-9138CCA74D8C","generation":0}]'
2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":,true,"peerIdentifier":"90045F83-13E2-42E6-8B7E-9138CCA74D8C","generation":0}'
,2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"90045F83-13E2-42E6-8B7E-9138CCA74D8C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 12:54:29 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"90045F83-13E2-42E6-8B7E-9138CCA74D8C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56CC6A57-6C82-4856-8C19-30E36C8EC7B7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4
[ThaliCore] Advertiser: session connected Peer(uuid: "56CC6A57-6C82-4856-8C19-30E36C8EC7B7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5
[ThaliCore] Advertiser: session connected Peer(uuid: "56CC6A57-6C82-4856-8C19-30E36C8EC7B7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55048
,2017-07-20 12:54:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":55048}'
,2017-07-20 12:54:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 90045F83-13E2-42E6-8B7E-9138CCA74D8C (syncValue: 1)'
,2017-07-20 12:54:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "90045F83-13E2-42E6-8B7E-9138CCA74D8C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "90045F83-13E2-42E6-8B7E-9138CCA74D8C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [5, 6, 9, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:54:32 - DEBUG testUtils: 'Got response data'
,2017-07-20 12:54:32 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4
,[ThaliCore] Session.session(_:peer:didChange:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4
[ThaliCore] Session.startOutputStream(with:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [5, 6, 9, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5
[ThaliCore] Session.startOutputStream(with:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [5, 6, 9, 15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "90045F83-13E2-42E6-8B7E-9138CCA74D8C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55054
,2017-07-20 12:54:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":55054}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [5, 6, 9, 15, 16, 17, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:54:35 - DEBUG testUtils: 'Got response data'
,2017-07-20 12:54:35 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,2017-07-20 12:54:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 12:54:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"90045F83-13E2-42E6-8B7E-9138CCA74D8C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:56CC6A57-6C82-4856-8C19-30E36C8EC7B7
,2017-07-20 12:54:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:54:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-20 12:54:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:54:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeS,treams() vsID:16
,ok 527 error should be null
,ok 528 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeS,treams() vsID:17
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [5, 6, 9, 15, 17, 18]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [5, 6, 9, 15, 18]
# setup
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] VirtualSocket.deinit vsID:15 [5, 6, 9, 18]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:55048
[ThaliCore] Session.disconnect() peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
,2017-07-20 12:54:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Session disconnected","portNumber":null}'
,2017-07-20 12:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:54:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-20 12:54:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[Th,aliCore] VirtualSocket.deinit vsID:18 [5, 6, 9]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisco,nnectHandler
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-20 12:54:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 530 error should be null
ok 531 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 532 getPeerIdentifier
ok 533 getConnectionType
ok 534 getActionType
,ok 535 getActionState
,ok 536 getPskIdentity
,ok 537 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 538 initial state
,ok 539 after start
,2017-07-20 12:54:39 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-20 12:54:39 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
ok 550 Entry exists
ok 551 Size must be 1
ok 552 Entry counter must be 2
ok 553 Entry exists
ok 554 Size must be 2
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
ok 574 Entries between 20 and MAXSIZE + 20 should exist
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
ok 584 Size should be MAXSIZE
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
ok 589 first enqueue is fine
ok 590 is an agent
ok 591 second enqueue is fine
ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
,ok 595 good enqueue
,ok 596 Identity should match
,2017-07-20 12:54:44 - DEBUG testUtils: 'Got response data'
,2017-07-20 12:54:44 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-20 12:54:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
ok 617 2nd good enqueue
ok 618 we are in the pool
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
,2017-07-20 12:54:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
,ok 634 Start should not be called
,ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-20 12:54:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-20 12:54:47 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 636 Got right error
,ok 637 Start should not be called
,ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-20 12:54:48 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 639 Got null
,2017-07-20 12:54:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 640 is an agent
,2017-07-20 12:54:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 642 Got Null
,ok 643 Got another null
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 644 is an agent
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 649 should have gotten null
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 650 Should have stopped nicely
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 654 Null 1
,ok 655 (unnamed assert)
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 656 is an agent
,ok 657 Null 3
,ok 658 Replication not yet called
,ok 659 Notification 2 not yet called
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 666 is an agent
,ok 667 First does not throw
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 668 is an agent
,ok 669 Second does not throw
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 670 is an agent
,ok 671 first ok
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 672 is an agent
ok 673 second ok
ok 674 third ok
,2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned, successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-20 12:54:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-20 12:54:52 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
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
,2017-07-20 12:54:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-20 12:54:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-20 12:54:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
,ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-20 12:54:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
ok 686 correct error message
,# teardown
,2017-07-20 12:54:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-07-20 12:54:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
,ok 691 Start after killed
,# teardown
,2017-07-20 12:54:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-07-20 12:54:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-20 12:54:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-07-20 12:55:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-20 12:55:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
,ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-20 12:55:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 702 publicKeysToNotify cannot be null
ok 703 ecdh for local device cannot be null
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
,2017-07-20 12:55:12 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 719 should be equal
,ok 720 should be equal
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
,ok 743 bluetooth peer's notification has correct connection type
,ok 744 tcp peer's notification has correct connection type
,2017-07-20 12:55:15 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-20 12:55:15 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 12:55:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
2017-07-20 12:55:15 - WARN thaliNotificationClient: 'peer is not available'
ok 746 notification peer dictionary does not contain any peers
,2017-07-20 12:55:15 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 12:55:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-07-20 12:55:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-20 12:55:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-07-20 12:55:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-20 12:55:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-20 12:55:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-20 12:55:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 12:55:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 12:55:20 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 12:55:20 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-07-20 12:55:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-20 12:55:23 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-20 12:55:23 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 769 peerDictionary should become empty
,# teardown
,2017-07-20 12:55:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-20 12:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
ok 771 peer state should be RESOLVED
,# teardown
,2017-07-20 12:55:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-20 12:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 772 First action failed
,ok 773 second action killed
# teardown
,2017-07-20 12:55:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-20 12:55:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-20 12:55:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-20 12:55:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-20 12:55:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-20 12:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
ok 794 should be 204
,# teardown
,2017-07-20 12:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-20 12:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-20 12:55:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
ok 798 should be 200
,ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
,ok 803 should be 204
,# teardown
,2017-07-20 12:55:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
ok 805 should be 204
,# teardown
,2017-07-20 12:55:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-07-20 12:55:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
,ok 808 not equal connection type
,ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-20 12:55:37 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-20 12:55:38 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 812 First start and on called correctly
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
,2017-07-20 12:55:38 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-20 12:55:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-20 12:55:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-20 12:55:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:55:40 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-20 12:55:40 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-20 12:55:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-20 12:55:40 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-20 12:55:40 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-07-20 12:55:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-20 12:55:41 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-20 12:55:41 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-20 12:55:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-20 12:55:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-20 12:55:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-20 12:55:45 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 12:55:45 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 12:55:48 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-07-20 12:55:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-20 12:55:50 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 12:55:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 12:55:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
ok 855 All tests passed!
,# teardown
,2017-07-20 12:55:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-20 12:55:54 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 12:55:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 12:55:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-20 12:55:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-20 12:55:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 12:55:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-20 12:56:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 12:56:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 860 action should be killed
ok 861 Error should be timed out
,# teardown
,2017-07-20 12:56:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-20 12:56:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-20 12:56:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'listening 55181'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] Browser.startListening
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:39C4BF82-C564-4703-A987-5D9BD291B6A0
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "96241CD7-C019-4F98-A006-9D7C1BEFED19", generation: 0)
2017-07-20 12:56:04 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"96241CD7-C019-4F98-A006-9D7C1BEFED19","generation":0}]'
2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"96241CD7-C019-4F98-A006-9D7C1BEFED19","generation":0}'
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"96241CD7-C019-4F98-A006-9D7C1BEFED19","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 12:56:04 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"96241CD7-C019-4F98-A006-9D7C1BEFED19","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 96241CD7-C019-4F98-A006-9D7C1BEFED19 (syncValue: 2)'
2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96241CD7-C019-4F98,-A006-9D7C1BEFED19", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "96241CD7-C019-4F98-A006-9D7C1BEFED19", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0)
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"22BF9314-137A-449F-AF79-3F7901B86A34","generation":0}]'
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"22BF9314-137A-449F-AF79-3F7901B86A34","generation":0}'
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"22BF9314-137A-449F-AF79-3F7901B86A34","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 12:56:04 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"22BF9314-137A-449F-AF79-3F7901B86A34","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "96241CD7-C019-4F98-A006-9D7C1BEFED19", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55184
,2017-07-20 12:56:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":55184}'
,2017-07-20 12:56:07 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 22BF9314-137A-449F-AF79-3F7901B86A34 (syncValue: 3)'
,2017-07-20 12:56:07 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Advertiser: session connected Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [5, 6, 9, 19]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Advertiser: session connected Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [5, 6, 9]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [5, 6, 9, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0 state: notConnected -> connecting
,2017-07-20 12:56:08 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [5, 6, 9, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [5, 6, 9, 20, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [5, 6, 9, 20, 21, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [5, 6, 9, 20, 21, 22, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:23 [5, 6, 9, 20, 21, 22, 24]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [5, 6, 9, 20, 21, 22, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [5, 6, 9, 20, 21, 22, 24]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [5, 6, 9, 20, 21, 22, 24, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [5, 6, 9, 20, 21, 22, 26]
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [5, 6, 9, 20, 21, 22, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [5, 6, 9, 20, 21, 22, 27]
,2017-07-20 12:56:09 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
,[ThaliCore] Session.session(_:peer:didChange:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0 state: connecting -> connected
[ThaliCore] Session.session(_:peer:didChange:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E state: connecting -> connected
[ThaliCore] ,Browser: session connected to Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55196
,2017-07-20 12:56:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":55196}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [5, 6, 9, 20, 21, 22, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [5, 6, 9, 20, 21, 22, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [5, 6, 9, 20, 21, 22, 27, 28, 29, 30]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [5, 6, 9, 20, 21, 22, 27, 29, 30]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [5, 6, 9, 20, 21, 22, 27, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [5, 6, 9, 20, 21, 22, 27, 30, 31]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [5, 6, 9, 20, 21, 22, 27, 30, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [5, 6, 9, 20, 21, 22, 27, 31, 32]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,3 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-20 12:56:11 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-20 12:56:11 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,0 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,2017-07-20 12:56:11 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 12:56:11 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:39 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37, 38, 40]
,2017-07-20 12:56:12 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37, 38, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37, 38, 40, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37, 38, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37, 38, 41, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37, 38, 41, 42, 43, 44]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,2017-07-20 12:56:12 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [5, 6, 9, 20, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37, 38, 41, 42, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-20 12:56:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-20 12:56:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:20
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:20 [5, 6, 9, 21, 22, 27, 31, 32, 33, 34, 35, 36, 37, 38, 41, 42, 43, 44, 45]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [5, 6, 9, 21, 27, 31, 32, 33, 34, 35, 36, 37, 38, 41, 42, 43, 44, 45]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [5, 6, 9, 21, 31, 32, 33, 34, 35, 36, 37, 38, 41, 42, 43, 44, 45]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
,[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:44 [5, 6, 9, 21, 31, 32, 33, 34, 35, 36, 37, 38, 41, 42, 43, 45]
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 12:56:13 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 12:56:13 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliC,ore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.,s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription,=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by ,remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] VirtualSocket.deinit vsID:32 [5, 6, 9, 21, 31, 33, 34, 35, 36, 37, 38, 41, 42, 43, 45]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count,:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] B,rowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] Bro,wserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [5, 6, 9, 21, 31, 33, 34, 36, 37, 38, 41, 42, 43, 45]
[ThaliCore] BrowserRelay.didCloseVirtualSocket,StreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:38 [5, 6, 9, 21, 31, 33, 34, 36, 37, 41, 42, 43, 45]
,[ThaliCore] VirtualSocket.deinit vsID:43 [5, 6, 9, 21, 31, 33, 34, 36, 37, 41, 42, 45]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[Thali,Core] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
,[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsI,D:34 [5, 6, 9, 21, 31, 33, 36, 37, 41, 42, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocket,DisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnec,tHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] VirtualSocket.deinit vsID:37 [5, 6, 9, 21, 31, 33, 36, 41, 42, 45]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [5, 6, 9, 21, 31, 33, 36, 41, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [5, 6, 9, 21, 33, 36, 41, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnec,t(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
,[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [5, 6, 9, 21, 33, 41, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:,withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [5, 6, 9, 21, 41, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [5, 6, 9, 21, 45]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [5, 6, 9, 21]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 12:59:04 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-20 12:59:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4,E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4,E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4,E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4,E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:03:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:03:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:03:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4,E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4,E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4,E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-20 13:06:03 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07,-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGG,ER result: passed - enqueue and run in order'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and en,queueAtTop'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously',
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-20 13:06:03 - INFO Coordinated,Client: '***TEST_LOGGER result: passed - another'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-20 13:06:04 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-20 13:06:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 867 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-20 13:06:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4,E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4,E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4,E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E6,8-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1301CBC2-597E-4E68-B4E8-B0509029AA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
