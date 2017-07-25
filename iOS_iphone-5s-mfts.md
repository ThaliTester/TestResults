#### Test 13228325722939a4_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/303A2CCE-FA45-46AF-9279-C85809ED2D99/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/303A2CCE-FA45-46AF-9279-C85809ED2D99/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app"
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,Current executable set to '/Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60710"
,(lldb)     command script import "/tmp/303A2CCE-FA45-46AF-9279-C85809ED2D99/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
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
,2017-07-25 16:23:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:23:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:23:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:23:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:23:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:23:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:23:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1A5974D4-DCD5-4123-A0,64-159175ECCC36", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1A5974D4-DCD5-4123-A064-159175ECCC36
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:29440DE8-671F-4AF0-B1CE-E9E0DB4E9D72
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C012D091-C063-4A47-A2BC-D0746024AC5E
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9CE847E6-4077-4183-80E1-7B92E408AAE0", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:9CE847E6-4077-4183-80E1-7B92E408AAE0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9CE847E6-4077-4183-80E1-7B92E408AAE0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9CE847E6-4077-4183-80E1-7B92E408AAE0", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-25 16:23:30 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.413008093833923
,2017-07-25 16:23:30 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-07-25 16:23:30 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9CE847E6-4077-4183-80E1-7B92E408AAE0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9CE847E6-4077-4183-80E1-7B92E408AAE0", generation: 0)
,2017-07-25 16:23:33 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-25 16:23:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-25 16:23:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-25 16:23:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-25 16:23:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-25 16:23:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-25 16:23:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-25 16:23:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-25 16:23:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-25 16:23:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-25 16:23:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-25 16:23:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-25 16:23:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-25 16:23:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-25 16:23:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-25 16:23:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-25 16:23:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-25 16:23:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-25 16:23:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-25 16:23:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-25 16:23:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-25 16:23:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-25 16:23:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-25 16:23:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-25 16:23:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-25 16:23:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-25 16:23:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-25 16:23:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-25 16:23:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-25 16:23:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-25 16:23:37 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-25 16:23:37 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-25 16:23:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:23:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:23:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:23:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:23:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:23:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:23:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:24:02 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-25 16:24:02 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-25 16:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-25 16:24:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-25 16:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-25 16:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-25 16:24:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-25 16:24:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-25 16:24:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-25 16:24:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,ok 26 secondPromise - second to run
,ok 27 secondPromise - in catch
,ok 28 firstPromise - third to run
,ok 29 firstPromise - in then
,ok 30 testing promises
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
,2017-07-25 16:24:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-25 16:24:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-25 16:24:18 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-25 16:24:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-25 16:24:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:63774255-0D9D-4FD6-809C-E2B054117309
[ThaliCore] Browser.startListening
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-25 16:24:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:22 - INFO tha,l,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:22 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:18DDBE83-783A-4D39-9C78-7CC2990A3E72
[ThaliCore] Browser.startListening
2017-07-25 16:24:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-25 16:24:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-07-25 16:24:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-25 16:24:23 - INFO thaliMobile: 'Received state ({"discoveryA,ctive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:24:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:24:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-25 16:24:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:25 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FCA821AA-0E67-4688-8276-63736B7F361E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FCA821AA-0E67-4688-8276-63736B7F361E
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FCA821AA-0E67-4688-8276-63736B7F361E
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A56653D7-4288-4BFA-8C93-751DE91C1EE7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A56653D7-4288-4BFA-8C93-751DE91C1EE7
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A56653D7-4288-4BFA-8C93-751DE91C1EE7", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:A56653D7-4288-4BFA-8C93-751DE91C1EE7
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A56653D7-4288-4BFA-8C93-751DE91C1EE7
[ThaliCore] Advertiser.stopAdvertising() peerID:A56653D7-4288-4BFA-8C93-751DE91C1EE7,
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:27 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:30 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0793BEDD-38B1-4AB4-A184-0B8B6241AD5C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0793BEDD-38B1-4AB4-A184-0B8B6241AD5C
2017-07-25 16:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:31, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-25 16:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:2CD50BF7-D808-4CB0-A1F4-BA064AF07FD4
[ThaliCore] Browser.startListening
2017-07-25 16:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,tisingActive":true}'
2017-07-25 16:24:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1584D9F-F535-451B-BC16-C39558E5F073:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1584D9F-F535-451B-BC16-C39558E5F073", generation: 0)
,ok 76 peers must be an array
ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0793BEDD-38B1-4AB4-A184-0B8B6241AD5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0793BEDD-38B1-4AB4-A184-0B8B6241AD5C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7B282771-861D-4DFE-84EC-9BD1796CBBD6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7B282771-861D-4DFE-84EC-9BD1796CBBD6", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0793BEDD-38B1-4AB4-A184-0B8B6241AD5C
2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,anged registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D2D0A921-E533-432A-9587-695A643E972C
2017-07-25 1,6:24:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DD5BBB9F-C625-4B4D-92C2-1F497D66583B
[Thal,i,Core] Browser.startListening
,2017-07-25 16:24:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:24:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:24:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,2017-07-25 16:24:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FABBB17E-2F2C-4F1E-8192-036793CA1965","generation":0}'
,2017-07-25 16:24:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FABBB17E-2F2C-4F1E-8192-036793CA1965 (syncValue: 95lLuF2OjGjNhHXTKaxQwiGtAUnoSQV9)'
,2017-07-25 16:24:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:24:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"58D6DF15-0B01-44D3-B565-43125AB2A311","generation":0}'
2017-07-25 16:24:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:24:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D2D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62767
2017-07-25 16:24:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"95lLuF2OjGjNhHXTKaxQwiGtAUnoSQV9","error":null,"portN,umber":62767}'
2017-07-25 16:24:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '95lLuF2OjGjNhHXTKaxQwiGtAUnoSQV9', error: 'null', listeningPort: '62767''
,2017-07-25 16:24:49 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-25 16:24:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 ,16:24:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-25 16:24:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D2D0A921-E533-432A-9587-6,95A643E972C
2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:FABBB17E-2F2C-4F1E-8192-036793CA1965
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62767
,[ThaliCore] Session.disconnect() peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A
2017-07-25 1,6:24:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:18D486AE-AFD3-48C7-92E4-8E0F17F10FA6
[ThaliCore] Browser.startListening
2017-07-25 16:24:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-25 16:24:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"58D6DF15-0B01-44D3-B565-43125AB2A311","generation":0}'
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 58D6DF15-0B01-44D3-B565-43125AB2A311 (syncValue: 4elxzjee6vkqQjzNaG1DvHcAbaAuG3rk)'
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
,2017-07-25 16:24:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B7B955AE-E51A-415A-B1E2-A27D544FD210","generation":0}'
,2017-07-25 16:24:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:24:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
,2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DA0E2C5F-B8AB-424C-989C-BDF114DA1928","generation":0}'
,2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-25 16:24:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4elxzjee6vkqQjzNaG1DvHcAbaAuG3rk","error":"Peer is unavailable","portNumber":null}'
,2017-07-25 16:24:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4elxzjee6vkqQjzNaG1DvHcAbaAuG3rk', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-25 16:24:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"58D6DF15-0B01-44D3-B565-43125AB2A311","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-25 16:24:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:24:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"58D6DF15-0B01-44D3-B565-43125AB2A311","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-25 16:24:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:24:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-25 16:24:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B7B955AE-E51A-415A-B1E2-A27D544FD210 (syncValue: uti6BFgWhgnKIB1A9mcV55vvipVYacm7)'
,2017-07-25 16:24:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:24:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62772
,2017-07-25 16:24:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uti6BFgWhgnKIB1A9mcV55vvipVYacm7","error":null,"portNumber":62772}'
,2017-07-25 16:24:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uti6BFgWhgnKIB1A9mcV55vvipVYacm7', error: 'null', listeningPort: '62772''
,Connecting to the localhost:62772
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,Connected to the localhost:62772
[ThaliCore] Session.startOutputStream(with:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
,2017-07-25 16:24:58 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-25 16:24:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:1
# teardown
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,2017-07-25 16:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 ,16:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-25 16:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DB38B4FE-1E0F-4F45-9FAA-A,91B54DC6C1A
2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:B7B955AE-E51A-415A-B1E2-A27D544FD210
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62772
[ThaliCore] Session.disconnect() peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:25:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:45CBB222-33C6-4C7F-9C48-5051955F679C
2017-07-25 1,6:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC
[Thal,i,Core] Browser.startListening
2017-07-25 16:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-25 16:25:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:09 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B7B955AE-E51A-415A-B1E2-A27D544FD210","generation":0}'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B7B955AE-E51A-415A-B1E2-A27D544FD210 (syncValue: QpEF7AiNjb0sTCaqBBmfBFgZvJYBQrRO)'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DA0E2C5F-B8AB-424C-989C-BDF114DA1928","generation":0}'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5A615210-A54A-4ECF-9E75-112BFEB948A6","generation":0}'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"82E20146-F4E8-4EC3-B45C-563776045682","generation":0}'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B7B955AE,-E51A-415A-B1E2-A27D544FD210 error: max retries exceeded
2017-07-25 16:25:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QpEF7AiNjb0sTCaqBBmfBFgZvJYBQrRO","error":"Connection could not be established","portNumber":null}'
2017-0,7-25 16:25:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QpEF7AiNjb0sTCaqBBmfBFgZvJYBQrRO', error: 'Connection could not be established', listeningPort: '%s''
2017-07-25 16:25:21 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"B7B955AE-E51A-415A-B1E2-A27D544FD210","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:25:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-25 16:25:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B7B955AE-E51A-415A-B1E2-A27D544FD210","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-25 16:25:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:21 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-25 16:25:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5A615210-A54A-4ECF-9E75-112BFEB948A6 (syncValue: HTyIW3X,qJJmAOeHv66h71JewYgLecz7d)'
2017-07-25 16:25:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5A615210-A54A,-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:25:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62779
2017-07-25 16:25:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HTyIW3XqJJmAOeHv66h71JewYgLecz7d",,"error":null,"portNumber":62779}'
2017-07-25 16:25:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HTyIW3XqJJmAOeHv66h71JewYgLecz7d', error: 'null', listeningPort: '62779''
,Connecting to the localhost:62779
Connecting to the localhost:62779
Connecting to the localhost:62779
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
Connected t,o the localhost:62779
,Connected to the localhost:62779
Connected to the localhost:62779
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
,ok 91 correct string length
,2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:294D0065-BE38-4005-A916-16306AC00B8B
[ThaliCore] Advertiser: session connected Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
[ThaliCore] Session.session(_:peer:didChange:) peer:294D0065-BE38-4005-A916-16306AC00B8B state: notConnected -> connecting
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,ok 92 correct string length
2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,ok 94 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [4]
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 96 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:294D0065-BE38-4005-A916-16306AC00B8B
,[ThaliCore] Session.session(_:peer:didChange:) peer:294D0065-BE38-4005-A916-16306AC00B8B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:294D0065-BE38-4005-A916-16306AC00B8B
,[ThaliCore] Session.startOutputStream(with:) peer:294D0065-BE38-4005-A916-16306AC00B8B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:294D0065-BE38-4005-A916-16306AC00B8B
[ThaliCore] Session.startOutputStream(with:) peer:294D0065-BE38-4005-A916-16306AC00B8B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:294D0065-BE38-4005-A916-16306AC00B8B
[ThaliCore] Session.startOutputStream(with:) peer:294D0065-BE38-4005-A916-16306AC00B8B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7, [4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Server received (9814 bytes):'
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Server received (8760 bytes):'
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Server received (7624 bytes):'
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
2017-07-25 16:25:27 - DEBUG testThaliMobileNative: 'Server received (11264 bytes):'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
2017-07-25 16:25:27 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [4, 6, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-25 16:25:27 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-25 16:25:27 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-25 16:25:27 - DEBUG testThaliMobileNative: 'Server data flu,shed'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [4, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [4]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disco,nnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-25 16:25:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:25:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:45CBB222-33C6-4C7F-9C48-5051955F679C
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:25:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:5A615210-A54A-4ECF-9E75-112BFEB948A6
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62779
[ThaliCore] Session.disconnect() p,eer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:294D0065-BE38-4005-A916-16306AC00B8B state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:294D0065-BE38-4005-A916-16306AC00B8B
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:294D0065-BE38-4005-A916-16306AC00B8B
[ThaliCore] Session.deinit peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-,07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:25:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BA8A39C9-4FC3-4403-9F86-8EC579378B0C
,2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EE089DA9-2DDC-4F9C-9C7D-18433029E756
[ThaliCore] Browser.startListening
,2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:25:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-25 16:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
2017-07-25 16:25:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5A615210-A54A-4ECF-9E75-112BFEB948A6","generation":0}'
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5A615210-A54A-4ECF-9E75-112BFEB948A6, (syncValue: qjSwduNUZTTT9X3F5CnER5lGUASlWvTB)'
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"82E20146-F4E8-4EC3-B45C-563776045682","generation":0}'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
2017-07-25 16:25:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"02A53CE0-2039-4785-8EFB-491EDF350756","generation":0}'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"891E67C8-0FC1-47E5-93ED-81CAFB5D34F9","generation":0}'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ED0BEEFA-FEFC-43DD-98A1-0802DBCC79D6
[ThaliCore] Advertiser: session connected Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ED0BEEFA-FEFC-43DD-98A1-0802DBCC79D6 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0BDE0016-0455-46FA-A315-6C05595FA621
[ThaliCore] Advertiser: session connected Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0BDE0016-0455-46FA-A315-6C05595FA621 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0BDE0016-0455-46FA-A315-6C05595FA621
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-25 16:25:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qjSwduNUZTTT9X3F5CnER5lGUASlWvTB","error":"Peer is unavailable",,"portNumber":null}'
2017-07-25 16:25:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qjSwduNUZTTT9X3F5CnER5lGUASlWvTB', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-25 16:25:37 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"5A615210-A54A-4ECF-9E75-112BFEB948A6","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:25:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-25 16:25:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5A615210-A54A-4ECF-9E75-112BFEB948A6","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-25 16:25:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-25 16:25:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 82E20146-F4E8-4EC3-B45C-563776045682 (syncValue: QgfSjzvJKpQRkCAHNHpZywWB81tLUlrU)'
,2017-07-25 16:25:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-25 16:25:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:0BDE0016-0455-46FA-A315-6C05595FA621 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ED0BEEFA-FEFC-43DD-98A1-0802DBCC79D6
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED0BEEFA-FEFC-43DD-98A1-0802DBCC79D6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ED0BEEFA-FEFC-43DD-98A1-0802DBCC79D6
[ThaliCore] Session.startOutputStream(with:) peer:ED0BEEFA-FEFC-43DD-98A1-0802DBCC79D6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [4, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-25 16:25:38 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-25 16:25:38 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-25 16:25:38 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-25 16:25:38 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-25 16:25:38 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [4]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BDE0016-0455-46FA-A315-6C05595FA621
[ThaliCore] Session.startOutputStream(with:) peer:0BDE0016-0455-46FA-A315-6C05595FA621
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [4, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-25 16:25:39 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-25 16:25:39 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-25 16:25:39 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes): '
,2017-07-25 16:25:39 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-25 16:25:39 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [4]
,[ThaliCore] Session.session(_:peer:didChange:) peer:82E20146-F4E8-4EC3-B45C-563776045682:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:82,E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,2E20146-F4E8-4EC3-B45C-563776045682", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:82E20146-F4E8-4EC3-B45C-563776045682:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:82,E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,2E20146-F4E8-4EC3-B45C-563776045682", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:82E20146-F4E8-4EC3-B45C-563776045682:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:82,E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,2E20146-F4E8-4EC3-B45C-563776045682", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:82E20146-F4E8-4EC3-B45C-563776045682:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:82,E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:82E20146,-F4E8-4EC3-B45C-563776045682 error: max retries exceeded
2017-07-25 16:25:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QgfSjzvJKpQRkCAHNHpZywWB81tLUlrU","error":"Connection could not be established","portNumber":null}'
2017-0,7-25 16:25:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QgfSjzvJKpQRkCAHNHpZywWB81tLUlrU', error: 'Connection could not be established', listeningPort: '%s''
2017-07-25 16:25:48 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"82E20146-F4E8-4EC3-B45C-563776045682","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:25:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-25 16:25:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"82E20146-F4E8-4EC3-B45C-563776045682","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-25 16:25:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-25 16:25:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 02A53CE0-2039-4785-8EFB-491EDF350756 (syncValue: SziNqIX,VmSZl1YGVuDpXZ8lj21IqRzOQ)'
2017-07-25 16:25:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:02A53CE0-2039,-4785-8EFB-491EDF350756:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:25:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62808
2017-07-25 16:25:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SziNqIXVmSZl1YGVuDpXZ8lj21IqRzOQ",,"error":null,"portNumber":62808}'
2017-07-25 16:25:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SziNqIXVmSZl1YGVuDpXZ8lj21IqRzOQ', error: 'null', listeningPort: '62808''
,Connecting to the localhost:62808
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [4, 10]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:62808
2017-07-25 16:25:51 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-25 16:25:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] T,CPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [4]
,2017-07-25 16:25:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:25:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:BA8A39C9-4FC3-4403-9F86-8EC579378B0C
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED0BEEFA-FEFC-43DD-98A1-0802DBCC79D6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0BDE0016-0455-46FA-A315-6C05595FA621
,[ThaliCore] BrowserManager.disconnect peer:02A53CE0-2039-4785-8EFB-491EDF350756
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62808
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:25:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,[ThaliCore] Session.deinit peer:0BDE0016-0455-46FA-A315-6C05595FA621
[ThaliCore] AdvertiserRelay.deinit
2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SziNqIXVmSZl1YGVuDpXZ8lj21IqRzOQ","error":"Session disconnected","portNumber":null}'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"02A53CE0-2039-4785-8EFB-491EDF350756","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"02A53CE0-2039-4785-8EFB-491EDF350756","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-25 16:25:52 - DEBUG thaliMobile,NativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1633D717-BAB5-409E-9E10-582EE947BE7C
,2017-07-25 16:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C7911950-5717-4E61-A056-1DDAA02CF1CB
[ThaliCore] Browser.startList,ening
2017-07-25 16:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:25:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
2017-07-25 16:25:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"02A53CE0-2039-4785-8EFB-491EDF350756","generation":0}'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 02A53CE0-2039-4785-8EFB-491EDF350756, (syncValue: 8nulrLKgPGvYDD1HxLn8e3NgPkZIAcFF)'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF3,50756", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo,:) found peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
,2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"891E67C8-0FC1-47E5-93ED-81CAFB5D34F9","generation":0}'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
2017-07-25 16:25:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"41B683AE-0F9D-4E22-8D46-1F9101EFBDED","generation":0}'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
2017-07-25 16:25:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D6DB2262-D0D6-4B7B-B142-443CB29EFA5D","generation":0}'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:02,A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,2A53CE0-2039-4785-8EFB-491EDF350756", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:02,A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,2A53CE0-2039-4785-8EFB-491EDF350756", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:02,A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,2A53CE0-2039-4785-8EFB-491EDF350756", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C532E667-106D-472C-ABF0-5903344AB907
[ThaliCore] Advertiser: session connected Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C532E667-106D-472C-ABF0-5903344AB907 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:02A53CE0-2039-4785-8EFB-491EDF350756:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:02,A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:02A53CE0,-2039-4785-8EFB-491EDF350756 error: max retries exceeded
2017-07-25 16:26:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8nulrLKgPGvYDD1HxLn8e3NgPkZIAcFF","error":"Connection could not be established","portNumber":null}'
2017-0,7-25 16:26:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8nulrLKgPGvYDD1HxLn8e3NgPkZIAcFF', error: 'Connection could not be established', listeningPort: '%s''
2017-07-25 16:26:06 - DEBUG thaliMobileNativeWrapper: 'Received ,peer availability changed event with {"peerIdentifier":"02A53CE0-2039-4785-8EFB-491EDF350756","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:26:06 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-25 16:26:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"02A53CE0-2039-4785-8EFB-491EDF350756","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-25 16:26:06 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:06 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-25 16:26:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 891E67C8-0FC1-47E5-93ED-81CAFB5D34F9 (syncValue: 5e3NVpE0ExYx81E7xAAAOQABd0gdKN5t)'
2017-07-25 16:26:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:891E67C8-0FC1,-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:26:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
2017-07-25 16:26:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C532E667-106D-472C-ABF0-5903344AB907
,[ThaliCore] Session.session(_:peer:didChange:) peer:C532E667-106D-472C-ABF0-5903344AB907 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C532E667-106D-472C-ABF0-5903344AB907
[ThaliCore] Session.startOutputStream(with:) peer:C532E667-106D-472C-ABF0-5903344AB907
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,1 [4, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (17449 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-25 16:26:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5e3NVpE0ExYx81E7xAAAOQABd0gdKN5t","error":"Peer is unavailable","portNumber":null}'
,2017-07-25 16:26:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5e3NVpE0ExYx81E7xAAAOQABd0gdKN5t', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-25 16:26:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"891E67C8-0FC1-47E5-93ED-81CAFB5D34F9","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-25 16:26:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"891E67C8-0FC1-47E5-93ED-81CAFB5D34F9","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-25 16:26:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-25 16:26:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-25 16:26:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 41B683AE-0F9D-4E22-8D46-1F9101EFBDED (syncValue: BDBUVbX45t7btCjsQRjsB5xu8CKphxG6)'
,2017-07-25 16:26:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:26:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (12045 bytes):'
,[ThaliCore] Session.deinit peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received (931 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:11 [4]
,[ThaliCore] Session.session(_:peer:didChange:) peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62827
2017-07-25 16:26:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BDBUVbX45t7btCjsQRjsB5xu8CKphxG6",,"error":null,"portNumber":62827}'
2017-07-25 16:26:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BDBUVbX45t7btCjsQRjsB5xu8CKphxG6', error: 'null', listeningPort: '62827''
,Connecting to the localhost:62827
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
Connected to the localhost:62827
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [4, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
,ok 102 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-25 16:26:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:26:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:1633D717-BAB5-409E-9E10-582EE947BE7C
2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16,:26:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62827
[ThaliCore] Session.disconnect() p,eer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C532E667-106D-472C-ABF0-5903344AB907 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C532E667-106D-472C-ABF0-5903344AB907
,[ThaliCore] Session.deinit peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:C532E667-106D-472C-ABF0-5903344AB907
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:44131FE1-8FED-48E6-877E-270274CFDD2F
[ThaliCore] Browser.startListening
2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-25 16:26:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7C11DC55-1A5C-4DA6-9974-2913C4B3F,7,ED
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
2017-07-25 16:26:16 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D6DB2262-D0D6-4B7B-B142-443CB29EFA5D","generation":0}]'
2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"D6DB2262-D0D6-4B7B-B142-443CB29EFA5D","generation":0}'
2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
2017-07-25 16:26:16 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"41B683AE-0F9D-4E22-8D46-1F9101EFBDED","generation":0}]'
,2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"41B683AE-0F9D-4E22-8D46-1F9101EFBDED","generation":0}'
,2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2934D003-1200-4C9E-AB23-8F76E83DCD2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2934D003-1200-4C9E-AB23-8F76E83DCD2A", generation: 0)
2017-07-25 16:26:16 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2934D003-1200-4C9E-AB23-8F76E83DCD2A","generation":0}]'
2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2934D003-1200-4C9E-AB23-8F76E83DCD2A","generation":0}'
2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 ,16:26:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-25 16:26:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7C11DC55-1A5C-4DA6-9974-2,913C4B3F7ED
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07,-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-25 16:26:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:84D2FC13-2F9A-43C7-A1F2-4CDD639E220C
[ThaliCore] Browser.startListening
ok 105 discoveryActive should be false
ok 106 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "769ED60A-EA80-44AA-87CD-BAB93306A9AD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:769ED60A-EA80-44AA-87CD-BAB9,3306A9AD
ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAd,vertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:769ED60A-EA80-44AA-87CD-BAB93306A9AD
,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-25 16:26:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-25 16:26:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-25 16:26:22 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-25 16:26:22 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-25 16:26:22 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:23 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-25 16:26:23 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:ff541983-c32c-4a5f-9365-a6b76aa0582a error: startListeningNotActive
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"nqO9Ws6JHH80UfVkxgYNrgS8OYz4MMky","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort ,is null
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ff541983-c32c-4a5f-9365-a6b76aa0582a","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:26:23 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ff541983-c32c-4a5f-9365-a6b76aa0582a","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:88E28EF8-1420-4C07-B4A6-5B98986C5328
,[ThaliCore] Browser.startListening
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-25 16:26:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
,ok 132 Got null as expected
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0vtPT7gtwWWE1JksTgeE6sEwCLODluqh","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-25 16:26:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1F1336E0-7CDC-4D36-8D75-16DCC2C5FEFA
,[ThaliCore] Browser.startListening
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-25 16:26:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
,ok 137 No error on starting
,ok 138 Got right error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
,# teardown
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D6DB2262-D0D6-4B7B-B142-443CB29EFA5D","generation":0}]'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D6DB2262-D0D6-4B7B-B142-443CB29EFA5D","generation":0}'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"41B683AE-0F9D-4E22-8D46-1F9101EFBDED","generation":0}]'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"41B683AE-0F9D-4E22-8D46-1F9101EFBDED","generation":0}'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:25 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:af361431-9a38-4959-8cdb-78f9bfc73619
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3638CC74-F640-40BF-A15A-F9FFB9A8E833
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F211700F-EAFA-4D3C-8CB7-EE7C96AB5E7E
,[ThaliCore] Browser.startListening
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:26:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
,2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D6DB2262-D0D6-4B7B-B142-443CB29EFA5D","generation":0}'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D6DB2262-D0D6-4B7B-B142-443CB29EFA5D (syncValue: Ug7IvC5AfnnzvSOHTw6P23c8nfZ9Dkii)'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"41B683AE-0F9D-4E22-8D46-1F9101EFBDED","generation":0}'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
,2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8B6F3729-5EF7-4FD4-95BD-D867B9E218E4","generation":0}'
,2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45A0ED46-6443-4763-9D77-FD1894FD6FB9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0)
2017-07-25 16:26:28 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45A0ED46-6443-4763-9D77-FD1894FD6FB9","generation":0}'
2017-07-25 16:26:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:28 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:26:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D6,DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D6,DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-25 16:26:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Ug7IvC5AfnnzvSOHTw6P23c8nfZ9Dkii","error":"Peer is unavailable",,"portNumber":null}'
2017-07-25 16:26:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Ug7IvC5AfnnzvSOHTw6P23c8nfZ9Dkii', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-25 16:26:32 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"D6DB2262-D0D6-4B7B-B142-443CB29EFA5D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:26:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-25 16:26:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D6DB2262-D0D6-4B7B-B142-443CB29EFA5D","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-25 16:26:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:32 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-25 16:26:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8B6F3729-5EF7-4FD4-95BD-D867B9E218E4 (syncValue: EzphAqYaDa0e2LBngw4rN0G,LDeiLDvne)'
2017-07-25 16:26:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8B6F3729-5EF7-4FD4-95BD-D867B,9E218E4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:26:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62840
2017-07-25 16:26:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EzphAqYaDa0e2LBngw4rN0GLDeiLDvne",,"error":null,"portNumber":62840}'
2017-07-25 16:26:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EzphAqYaDa0e2LBngw4rN0GLDeiLDvne', error: 'null', listeningPort: '62840''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
,ok 143 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0) found active relay
,2017-07-25 16:26:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XITmQ2wsySK4Dqo9bA5obk6tnb90eS1z","error":null,"portNumber":62840}'
,ok 144 No error
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [4, 12, 13]
,ok 145 Ports equal
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0) found active relay
,2017-07-25 16:26:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6cGC091vUjblfVFyHdidbS98hHyKEee6","error":null,"portNumber":62840}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B1FF8E98-5CD7-4FDF-83DE-B235AE46F72C
[ThaliCore] Advertiser: session connected Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B1FF8E98-5CD7-4FDF-83DE-B235AE46F72C state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B1FF8E98-5CD7-4FDF-83DE-B235AE46F72C
,[ThaliCore] Session.session(_:peer:didChange:) peer:B1FF8E98-5CD7-4FDF-83DE-B235AE46F72C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B1FF8E98-5CD7-4FDF-83DE-B235AE46F72C
[ThaliCore] Session.startOutputStream(with:) peer:B1FF8E98-5CD7-4FDF-83DE-B235AE46F72C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [4, 12, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-25 16:26:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:26:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:3638CC74-F640-40BF-A15A-F9FFB9A8E833
2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16,:26:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeS,treams() vsID:14
,[ThaliCore] BrowserManager.disconnect peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62840
[ThaliCore] VirtualSocket.closeStr,eams() vsID:13
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [4, 12, 13]
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:13 [4, 12]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
,[ThaliCore] Session.deinit peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:B1FF8E98-5CD7-4FDF-83DE-B235AE46F72C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B1FF8E98-5CD7-4FDF-83DE-B235AE46F72C
[ThaliCore] AdvertiserRelay.deinit
,# initial peer discovery
,2017-07-25 16:26:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,[ThaliCore] Session.deinit peer:B1FF8E98-5CD7-4FDF-83DE-B235AE46F72C
# teardown
,2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-25 16:26:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-25 16:26:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-25 16:26:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-25 16:26:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-25 16:26:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-25 16:26:49 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-25 16:26:49 - DEBUG createNativeListener: 'listening 62844'
ok 149 Should throw
,# teardown
,2017-07-25 16:26:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:49 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 62846'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 62849'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 62853'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 62858'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'listening 62862'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-25 16:26:51 - DEBUG createNativeListener: 'listening 62866'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-25 16:26:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'listening 62870'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-25 16:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-25 16:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'listening 62874'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-25 16:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-25 16:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-25 16:26:54 - DEBUG createNativeListener: 'listening 62926'
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-25 16:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-25 16:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'listening 62930'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-25 16:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-25 16:26:56 - DEBUG createNativeListener: 'listening 62933'
ok 196 port must be in range
,# teardown
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'listening 62934'
,ok 197 second start should return same port
,# teardown
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'listening 62936'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-25 16:26:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-25 16:26:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-25 16:26:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 62938
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:56E48F0C-5C40-4592-82B8-A52B84B2813F
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:26:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:26:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:117E516B-B78F-493E-A3A5-2C5D5138CE0D
,[ThaliCore] Browser.startListening
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:26:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-25 16:26:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45A0ED46-6443-4763-9D77-FD1894FD6FB9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B037CFD3-4481-4DF6-9B8E-99CE54716E19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B037CFD3-4481-4DF6-9B8E-99CE54716E19", generation: 0)
2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45A0ED46-6443-4763-9D77-FD1894FD6FB9","generation":0}'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 45A0ED46-6443-4763-9D77-FD1894FD6FB9 (syncValue: 7uRLFVF3cA8FZvq98aMZ5HFJoCkiekwU)'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:45A0ED46-6443-4763-9D77-FD1894FD6FB9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B037CFD3-4481-4DF6-9B8E-99CE54716E19","generation":0}'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:56E48F0C-5C40-4592-82B8-A52B84B2813F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A3E339D2-70CF-4D85-BCE6-50D4FB63BF85:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0)
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A3E339D2-70CF-4D85-BCE6-50D4FB63BF85","generation":0}'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8B6F3729-5EF7-4FD4-95BD-D867B9E218E4","generation":0}'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:45A0ED46-6443-4763-9D77-FD1894FD6FB9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:45A0ED46-6443-4763-9D77-FD1894FD6FB9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:45,A0ED46-6443-4763-9D77-FD1894FD6FB9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,5A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-25 16:27:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7uRLFVF3cA8FZvq98aMZ5HFJoCkiekwU","error":"Peer is unavailable","portNumber":null}'
,2017-07-25 16:27:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7uRLFVF3cA8FZvq98aMZ5HFJoCkiekwU', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-25 16:27:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"45A0ED46-6443-4763-9D77-FD1894FD6FB9","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-25 16:27:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:27:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"45A0ED46-6443-4763-9D77-FD1894FD6FB9","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-25 16:27:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:27:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-25 16:27:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B037CFD3-4481-4DF6-9B8E-99CE54716E19 (syncValue: GFN388Czj8fAUPktVHfLoQy3l7Lu3JQN)'
,2017-07-25 16:27:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B037CFD3-4481-4DF6-9B8E-99CE54716E19", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B037CFD3-4481-4DF6-9B8E-99CE54716E19", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B037CFD3-4481-4DF6-9B8E-99CE54716E19:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:27:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:45A0ED46-6443-4763-9D77-FD1894FD6FB9:0
[ThaliCore] BrowserRelay.deinit
,2017-07-25 16:27:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B037CFD3-4481-4DF6-9B8E-99CE54716E19:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B037CFD3-4481-4DF6-9B8E-99CE54716E19:0
,2017-07-25 16:27:04 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B037CFD3-4481-4DF6-9B8E-99CE54716E19:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "B037CFD3-4481-4DF6-9B8E-99CE54716E19", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62946
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GFN388Czj8fAUPktVHfLoQy3l7Lu3JQN","error":null,"portNumber":62946}'
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GFN388Czj8fAUPktVHfLoQy3l7Lu3JQN', error: 'null', listeningPort: '62946''
,ok 210 should be equal
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A3E339D2-70CF-4D85-BCE6-50D4FB63BF85 (syncValue: yuSAYcUCDcXVqipNM46SHEdWg7vqek4O)'
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A3E339D2-70CF-4D85-BCE6-50D4FB63BF85:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-25 16:27:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A3E339D2-70CF-4D85-BCE6-50D4FB63BF85:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:19C99E7C-5CB4-47FC-985C-860D669DEBF5
[ThaliCore] Advertiser: session connected Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:19C99E7C-5CB4-47FC-985C-860D669DEBF5 state: notConnected -> connecting
,2017-07-25 16:27:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0EA925B4-0B46-484F-8B3B-75C44871A9AD
[ThaliCore] Advertiser: session connected Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0EA925B4-0B46-484F-8B3B-75C44871A9AD state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A3E339D2-70CF-4D85-BCE6-50D4FB63BF85:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A3E339D2-70CF-4D85-BCE6-50D4FB63BF85:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62951
2017-07-25 16:27:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yuSAYcUCDcXVqipNM46SHEdWg7vqek4O",,"error":null,"portNumber":62951}'
2017-07-25 16:27:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yuSAYcUCDcXVqipNM46SHEdWg7vqek4O', error: 'null', listeningPort: '62951''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:19C99E7C-5CB4-47FC-985C-860D669DEBF5
,[ThaliCore] Session.session(_:peer:didChange:) peer:19C99E7C-5CB4-47FC-985C-860D669DEBF5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0EA925B4-0B46-484F-8B3B-75C44871A9AD
,[ThaliCore] Session.session(_:peer:didChange:) peer:0EA925B4-0B46-484F-8B3B-75C44871A9AD state: connecting -> connected
,2017-07-25 16:27:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4,F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4,F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-25 16:28:07 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07,-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGG,ER result: passed - enqueue and run in order'
2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and en,queueAtTop'
2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously',
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-25 16:28:07 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Single coordinated request ios native, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE,61F1/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/tim,ers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-07-25 16:28:07 - ERROR Coordi,natedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-25 16:28:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4,F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4,F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:28 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:350:16
$9@timers.,js:120:1
''
,2017-07-25 16:30:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4,F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4,F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4,F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4,F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4,F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4,F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F3,3-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:37 - ERROR CoordinatedClient: 'reconnect_failed error: 'undefined', description: '%s,', stack: '%s''
2017-07-25 16:43:37 - DEBUG CoordinatedClient: 'test client failed'
2017-07-25 16:43:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: ',Transport.prototype.onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/container,s/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jx,core/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FB6B2EB-5E57-4F33-B728-8AAF88FE61F1/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16,:43:37 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-07-25 16:43:37 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
