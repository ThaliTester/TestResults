#### Test 1271987109197780_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1271987109197780/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/593E1CC4-C14D-4A19-8198-E12F4894AB42/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/593E1CC4-C14D-4A19-8198-E12F4894AB42/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1271987109197780/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1271987109197780/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63209"
,(lldb)     command script import "/tmp/593E1CC4-C14D-4A19-8198-E12F4894AB42/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,2017-07-17 11:37:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:37:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:37:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:37:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:37:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:37:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:37:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC69EA8D-8D02-48FE-9E,88-EB01B797CBCA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EC69EA8D-8D02-48FE-9E88-EB01B797CBCA
Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserMana,ger.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3398905A-2EB7-4561-A1F9-044BAE323256
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOn,StartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D4191DCD-003E-4CC6-BCAB-9C0EF6506643
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.star,tUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9BE8DB5D-1B86-42D4-BD7A-5D170823E51F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9BE8DB5D-1B86-42D4-BD7A-5D170823E51F
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9BE8DB5D-1B86-42D4-BD7A-5D170823E51F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9BE8DB5D-1B86-42D4-BD7A-5D170823E51F", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-17 11:37:18 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.478124976158142
,2017-07-17 11:37:18 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-07-17 11:37:18 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9BE8DB5D-1B86-42D4-BD7A-5D170823E51F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9BE8DB5D-1B86-42D4-BD7A-5D170823E51F", generation: 0)
,2017-07-17 11:37:21 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-17 11:37:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-17 11:37:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-17 11:37:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-17 11:37:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-17 11:37:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-17 11:37:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-17 11:37:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-17 11:37:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-17 11:37:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-17 11:37:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-17 11:37:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-17 11:37:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-17 11:37:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-17 11:37:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-17 11:37:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-17 11:37:25 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-17 11:37:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:38:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:38:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:38:17 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-17 11:38:17 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-17 11:38:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-17 11:38:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-17 11:38:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-17 11:38:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-17 11:38:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-17 11:38:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-17 11:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-17 11:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-17 11:38:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-17 11:38:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-17 11:38:52 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 51 participant data matches
,ok 52 test participant has uuid
,ok 53 participant data matches
,ok 54 test participant has uuid
,ok 55 participant data matches
,ok 56 own UUID is found from the participants list
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
,2017-07-17 11:38:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-17 11:39:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FD2ABAF3-3E8B-4BB2-A3CC-90598F01119C
[ThaliCore] Browser.startListening
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:39:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F6F839CA-34F5-4B71-BD86-CF31FD80067A
[ThaliCore] Browser.startListening
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Received state ({"discoveryA,c,tive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teard,own
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B3E20E25-BE74-444E-B109-5D0BC9214DAA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B3E20E25-BE74-444E-B109-5D0BC9214DAA
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B3E20E25-BE74-444E-B109-5D0BC9214DAA
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-17 11:39:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1DA8BD41-52C5-42DC-81AE-4937BBFCA46E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1DA8BD41-52C5-42DC-81AE-4937BBFCA46E
2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:07, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(,onPort:errorHandler:) Peer(uuid: "1DA8BD41-52C5-42DC-81AE-4937BBFCA46E", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:1DA8BD41-52C5-42DC-81AE-4937BBFCA46E
2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingS,tateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:1DA8BD41-52C5-42DC-81AE-4937BBFCA46E
,[ThaliCore] Advertiser.stopAdvertising() peerID:1DA8BD41-52C5-42DC-81AE-4937BBFCA46E
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive",:false}'
2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9C18C89B-A44E-40BB-8874-BA0D3F15CFC3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9C18C89B-A44E-40BB-8874-BA0D3F15CFC3
2017-07-17 1,1:39:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4E390188-F06D-45FC-A7F3-F86DCF05016A
,[ThaliCore] Browser.startListening
2017-07-17 11:39:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:39:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-17 11:39:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:072F8955-002F-4FB8-B690-7FD6A3751092:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "072F8955-002F-4FB8-B690-7FD6A3751092", generation: 0)
ok 88 peers must be an array,
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:71CDA35F-9267-45B6-A828-FDA702B4717C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "71CDA35F-9267-45B6-A828-FDA702B4717C", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 93 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9C18C89B-A44E-40BB-8874-BA0D3F15CFC3
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 94 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:613A62B9-F503-4283-BB13-6AFB671D570F
2017-07-17 1,1:39:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4B65DE7B-3539-4B12-BB30-BD0032967742
[ThaliCore] Browser.startListening
2017-07-17 11:39:21 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:39:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0A4575A2-3A49-41BB-BD72-8B94BB6A9FC9
,[ThaliCore] Advertiser: session connected Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0A4575A2-3A49-41BB-BD72-8B94BB6A9FC9 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ED603480-941C-456A-A3C0-F97D1C3EED1B
[ThaliCore] Advertiser: session connected Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ED603480-941C-456A-A3C0-F97D1C3EED1B state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3D697D64-8E3B-41E6-AC54-F02BB2C336FA", generation: 0)
2017-07-17 11:39:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3D697D64-8E3B-41E6-AC54-F02BB2C336FA","generation":0}'
2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3D697D64-8E3B-41E6-AC54-F02BB2C336FA (syncValue: ePvk2ImKCxL95i1KTpJOmyA0e5a3jYIN)'
2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3D697D64-8E3B-41E6-AC54-F02BB2C336FA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3D697D64-8E3B-41E6-AC54-F02BB2C336FA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
,2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6D26B543-6D86-4464-9151-F821BBB0AE6A","generation":0}'
,2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ED603480-941C-456A-A3C0-F97D1C3EED1B
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED603480-941C-456A-A3C0-F97D1C3EED1B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0A4575A2-3A49-41BB-BD72-8B94BB6A9FC9
,[ThaliCore] Session.session(_:peer:didChange:) peer:0A4575A2-3A49-41BB-BD72-8B94BB6A9FC9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3D697D64-8E3B-41E6-AC54-F02BB2C336FA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52337
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ePvk2ImKCxL95i1KTpJOmyA0e5a3jYIN","error":null,"portNumber":52337}'
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ePvk2ImKCxL95i1KTpJOmyA0e5a3jYIN', error: 'null', listeningPort: '52337''
,2017-07-17 11:39:25 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,2017-07-17 11:39:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 ,11:39:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-17 11:39:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising() peerID:613A62B9-F503-4283-BB13-6AFB671D570F
2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:25 ,-, INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52337
,[ThaliCore] Session.disconnect() peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0A4575A2-3A49-41BB-BD72-8B94BB6A9FC9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:ED603480-941C-456A-A3C0-F97D1C3EED1B
,[ThaliCore] Session.deinit peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:ED603480-941C-456A-A3C0-F97D1C3EED1B
[ThaliCore] AdvertiserRelay.deinit
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E8D0C536-7136-43E6-A780-C955908E4A7D
2017-07-17 1,1:39:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9D7996ED-C4B3-4E8B-A736-13A79E300A64
[Thal,iCore] Browser.startListening
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:39:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0,)
,2017-07-17 11:39:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EB99FC28-FDE5-47DF-88AC-5B18CA1373EE","generation":0}'
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EB99FC28-FDE5-47DF-88AC-5B18CA1373EE (syncValue: rXxI4oFi1izS4PIOdt6e6bgrL8TvQTLk)'
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09DC3B5D-BE85-4C89-8D0B-68348FA2CA72","generation":0}'
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6D26B543-6D86-4464-9151-F821BBB0AE6A","generation":0}'
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52341
,2017-07-17 11:39:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rXxI4oFi1izS4PIOdt6e6bgrL8TvQTLk","error":null,"portNumber":52341}'
,2017-07-17 11:39:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rXxI4oFi1izS4PIOdt6e6bgrL8TvQTLk', error: 'null', listeningPort: '52341''
,Connecting to the localhost:52341
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
,Connected to the localhost:52341
,2017-07-17 11:39:31 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,2017-07-17 11:39:31 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:1
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
,2017-07-17 11:39:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 ,11:39:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising() peerID:E8D0C536-7136-43E6-A780-C955908E4A7D
2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:35 ,-, INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE
[ThaliCore] B,rowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52341
[ThaliCore] Session.disconnect() peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
[ThaliCore] TCPListener.socketDidDisconnect(_:with,Error:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:523A7280-3273-4765-AF24-D29D03483576
2017-07-17 1,1:39:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B
[Tha,liCore] Browser.startListening
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:39:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
2017-07-17 11:39:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09DC3B5D-BE85-4C89-8D0B-68348FA2CA72","generation":0}'
2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 09DC3B5D-BE85-4C89-8D0B-68348FA2CA72, (syncValue: aOWHpH4OnfoEVH5ecv966tcjoRH0iFqf)'
2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA,2CA72", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"EB99FC28-FDE5-47DF-88AC-5B18CA1373EE","generation":0}'
,2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"E0CF7079-E931-4613-8F13-41A68FDA7BF3","generation":0}'
2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
,2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4B7E8D7E-A7F8-444B-9652-0AE90AED8376","generation":0}'
,2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,9DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,9DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:09DC3B5D,-BE85-4C89-8D0B-68348FA2CA72 error: max retries exceeded
2017-07-17 11:39:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aOWHpH4OnfoEVH5ecv966tcjoRH0iFqf","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:39:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'aOWHpH4OnfoEVH5ecv966tcjoRH0iFqf', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:39:41 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"09DC3B5D-BE85-4C89-8D0B-68348FA2CA72","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:39:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-17 11:39:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"09DC3B5D-BE85-4C89-8D0B-68348FA2CA72","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-17 11:39:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:41 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-17 11:39:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E0CF7079-E931-4613-8F13-41A68FDA7BF3 (syncValue: bYNQw2Y,0zKX5yIrtZxDeJTzXfgtI3tbb)'
2017-07-17 11:39:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E0CF7079-E931,-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:39:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52350
2017-07-17 11:39:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bYNQw2Y0zKX5yIrtZxDeJTzXfgtI3tbb",,"error":null,"portNumber":52350}'
2017-07-17 11:39:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bYNQw2Y0zKX5yIrtZxDeJTzXfgtI3tbb', error: 'null', listeningPort: '52350''
Connecting to the localhost:52350
Connecting to th,e localhost:52350
Connecting to the localhost:52350
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[Th,aliCore] TCPListener.socket(_:didAcceptNewSocket:)
Connected to the localhost:52350
Connected to the localhost:52350
,Connected to the localhost:52350
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
,[ThaliCore] Session.startOutputStream(with:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4]
,ok 112 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:3 [4]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:4 []
,ok 113 got the same data back
,ok 114 got the same data back
,# teardown
,2017-07-17 11:39:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:523A7280-3273-4765-AF24-D29D03483576
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52350
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bYNQw2Y0zKX5yIrtZxDeJTzXfgtI3tbb","error":"Session disconnected","portNumber":null}'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E0CF7079-E931-4613-8F13-41A68FDA7BF3","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E0CF7079-E931-4613-8F13-41A68FDA7BF3","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
,[ThaliCore] BrowserRelay.deinit
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3C438B2A-C00A-4678-9E5E-055F2C6,D4DEB
[ThaliCore] Browser.startListening
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
2017-07-17 11:39:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E0CF7079-E931-4613-8F13-41A68FDA7BF3","generation":0}'
2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E0CF7079-E931-4613-8F13-41A68FDA7BF3, (syncValue: hgPHd9wYngD2aWqAeOLsDzKqxnRdInaM)'
2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FD,A7BF3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
,2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4B7E8D7E-A7F8-444B-9652-0AE90AED8376","generation":0}'
2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0,CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15599E72-C57A-4218-B314-C9C3FB7E4346:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15599E72-C57A-4218-B314-C9C3FB7E4346", generation: 0)
2017-07-17 11:39:47 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"58491740-8F67-4D72-A396-FDAC62354394","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
2017-07,-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already r,unning test!'
2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"15599E72-C57A-4218-B314-C9C3FB7E4346","generation":0}'
,2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0,CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0,CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0,CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:E0CF7079,-E931-4613-8F13-41A68FDA7BF3 error: max retries exceeded
2017-07-17 11:39:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hgPHd9wYngD2aWqAeOLsDzKqxnRdInaM","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:39:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hgPHd9wYngD2aWqAeOLsDzKqxnRdInaM', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:39:50 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"E0CF7079-E931-4613-8F13-41A68FDA7BF3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:39:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-17 11:39:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E0CF7079-E931-4613-8F13-41A68FDA7BF3","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-17 11:39:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:50 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-17 11:39:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 58491740-8F67-4D72-A396-FDAC62354394 (syncValue: ZNxwsVK,d6ZdggF8tgXAAwmliDANMTU1Y)'
2017-07-17 11:39:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:58491740-8F67,-4D72-A396-FDAC62354394:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:39:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:61D3DCD6-0405-4EDE-B701-B6A0D2E19893
[ThaliCore] Advertiser: session connected Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:61D3DCD6-0405-4EDE-B701-B6A0D2E19893 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:58491740-8F67-4D72-A396-FDAC62354394:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:58491740-8F67-4D72-A396-FDAC62354394:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:61D3DCD6-0405-4EDE-B701-B6A0D2E19893
,[ThaliCore] Session.session(_:peer:didChange:) peer:58491740-8F67-4D72-A396-FDAC62354394:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52370
,2017-07-17 11:39:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZNxwsVKd6ZdggF8tgXAAwmliDANMTU1Y","error":null,"portNumber":52370}'
,2017-07-17 11:39:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZNxwsVKd6ZdggF8tgXAAwmliDANMTU1Y', error: 'null', listeningPort: '52370''
,[ThaliCore] Session.session(_:peer:didChange:) peer:61D3DCD6-0405-4EDE-B701-B6A0D2E19893 state: connecting -> connected
,Connecting to the localhost:52370
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:58491740-8F67-4D72-A396-FDAC62354394:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:61D3DCD6-0405-4EDE-B701-B6A0D2E19893
,[ThaliCore] Session.startOutputStream(with:) peer:61D3DCD6-0405-4EDE-B701-B6A0D2E19893
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [5]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:58491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Server received psk id: psk-id
,Connected to the localhost:52370
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [6]
,ok 119 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-17 11:39:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09
2017-07-17 11:39:54 - DEBUG thaliMobileNativeWr,apper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisi,ngAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:58491740-8F67-4D72-A396-FDAC62354394
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52370
[ThaliCore] Session.disconnect() peer:58491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:58491740-8F67-4D72-A396-FDAC62354394:0
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:61D3DCD6-0405-4EDE-B701-B6A0D2E19893 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:61D3DCD6-0405-4EDE-B701-B6A0D2E19893
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:61D3DCD6-0405-4EDE-B701-B6A0D2E19893
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5FA8589D-0E52-4FB5-86A3-8C265869ADC1
,2017-07-17 11:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:39:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8BABBB55-79ED-47D1-8E13-FC6391DA4CFC
,[ThaliCore] Browser.startListening
2017-07-17 11:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:39:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
2017-07-17 11:39:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E0CF7079-E931-4613-8F13-41A68FDA7BF3","generation":0}'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E0CF7079-E931-4613-8F13-41A68FDA7BF3, (syncValue: fYuE71c73pqsnSLMozfeBC6giJe2QcTl)'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCor,e] BrowserManager.foundPeerHandler peer:Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0) creat,ing a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[,ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"58491740-8F67-4D72-A396-FDAC62354394","generation":0}'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!',
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}'
2017-07-,17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09BB567D-7B1E-4093-B10E-64E73CF5C4BE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09BB567D-7B1E-4093-B10E-64E73CF5C4BE", generation: 0)
2017-07-17 11:39:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09BB567D-7B1E-4093-B10E-64E73CF5C4BE","generation":0}'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:56 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0,CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:58491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0,CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0,CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0,CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:E0CF7079,-E931-4613-8F13-41A68FDA7BF3 error: max retries exceeded
2017-07-17 11:40:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fYuE71c73pqsnSLMozfeBC6giJe2QcTl","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:40:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fYuE71c73pqsnSLMozfeBC6giJe2QcTl', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:40:00 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"E0CF7079-E931-4613-8F13-41A68FDA7BF3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:40:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-17 11:40:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E0CF7079-E931-4613-8F13-41A68FDA7BF3","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-17 11:40:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-17 11:40:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8763C22E-349D-4875-B6BD-8F71D8CD3697 (syncValue: a1bD7yf,MO9hej5xsLwSlr2mrXhJGbGBF)'
2017-07-17 11:40:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8763C22E-349D,-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:40:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52385
2017-07-17 11:40:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"a1bD7yfMO9hej5xsLwSlr2mrXhJGbGBF",,"error":null,"portNumber":52385}'
2017-07-17 11:40:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'a1bD7yfMO9hej5xsLwSlr2mrXhJGbGBF', error: 'null', listeningPort: '52385''
,Connecting to the localhost:52385
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,Connected to the localhost:52385
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,ok 124 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-17 11:40:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:40:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5FA8589D-0E52-4FB5-86A3-8C265869ADC1
2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,o,nTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:8763C22E-349D-4875-B6BD-8F71D8CD3697
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectio,nsAndDisconnectClients() port:52385
[ThaliCore] Session.disconnect() peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:03FE996B-8AB5-43C0-B3B2-8862A69D693A
[ThaliCore] Browser.startListening
2017-07-17 11:40:07 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:40:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-17 11:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:,errorHandler:) Peer(uuid: "D0E56831-394E-47D9-BA4F-82F9ECB0DA87", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D0E56831-394E-47D9-BA4F-82F9ECB0DA87
,2017-07-17 11:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:40:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-17 11:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,2017-07-17 11:40:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}]'
,2017-07-17 11:40:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}'
,2017-07-17 11:40:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C22ED207-1690-4275-814E-7C3ED1327DC2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C22ED207-1690-4275-814E-7C3ED1327DC2", generation: 0)
,2017-07-17 11:40:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C22ED207-1690-4275-814E-7C3ED1327DC2","generation":0}]'
,2017-07-17 11:40:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C22ED207-1690-4275-814E-7C3ED1327DC2","generation":0}'
,2017-07-17 11:40:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0E56831-394E-47D9-BA4F-82F9ECB0DA87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0E56831-394E-47D9-BA4F-82F9ECB0DA87", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:40:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D0E56831-394E-47D9-BA4F-82F9ECB0DA87
2017-07-17 ,11:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130, ,Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-17 11:40:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:90451B59-F3DE-410F-87AF-EDE08BC1A832
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "98F52520-62E6-4AD6-BB3C-96472E45C184", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:98F52520-62E6-4AD6-BB3C-96472E45C184
,ok 135 discoveryActive should be false
,ok 136 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 137 discoveryActive should be false
ok 138 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAd,vertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:98F52520-62E6-4AD6-BB3C-96472E45C184
,ok 139 discoveryActive should be false
ok 140 advertisingActive should be true
,ok 141 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 142 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 143 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-17 11:40:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-17 11:40:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-17 11:40:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:16 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 147 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-17 11:40:16 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
,2017-07-17 11:40:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-17 11:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-17 11:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-17 11:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 154 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2ed0a841-d150-4bdd-b36b-66de96fb3403 error: startListeningNotActive
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"pOuh8k43529Y3LffClMRjOCgeDVxrL15","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 157 Should only get called after multiConnect returned
ok 158 SyncValue matches
ok 159 Got right error
ok 160 listeningPort ,is null
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2ed0a841-d150-4bdd-b36b-66de96fb3403","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:40:18 - DEBUG t,haliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2ed0a841-d150-4bdd-b36b-6,6,de96fb3403","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 161 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 162 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:67BAC996-AF1E-4EE8-A63E-4B4681BFF44E
[ThaliCore] Browser.startListening
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 No error on starting
,ok 164 Got null as expected
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NtprbhFwEWO4eAAMbagv8Mr67Bp48Tq2","error":"Illegal peerID","portNumber":null}'
,ok 165 Should only get called after multiConnect returned
,ok 166 SyncValue matches
,ok 167 Got right error
,ok 168 listeningPort is null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}]'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 169 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 170 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-17 11:40:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 172 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BA7F8C54-FF53-4EFE-994C-B4A8368BECBF
[ThaliCore] Browser.startListening
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:40:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 173 No error on starting
,ok 174 Got right error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
# teardown
2017-07-17 11:40:,19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}]'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 175 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 176 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 177 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 178 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:19 -, DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 179 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:8eb13631-4b7d-4386-9163-eb0e83a05556
,ok 180 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 181 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 182 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6396697D-E678-496B-A513-1569FA649E5E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6396697D-E678-496B-A513-1569FA649E5E
2017-07-17 1,1:40:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:40:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 183 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4849B908-940A-4C79-8626-203B01FEA846
[ThaliCore] Browser.startListening
2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-17 11:40:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 184 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8763C22E-349D-4875-B6BD-8F71D8CD3697 (syncValue: kzYUeNS0mMCOmXEie35QWCusJNdk30IZ)'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","generation":0}'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3C2C6DFD-3481-46B7-BF2E-3B8B8326D366","generation":0}'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6396697D-E678-496B-A513-1569FA649E5E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6396697D-E678-496B-A513-1569FA649E5E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:87,63C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:87,63C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:87,63C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:8763C22E,-349D-4875-B6BD-8F71D8CD3697 error: max retries exceeded
2017-07-17 11:40:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kzYUeNS0mMCOmXEie35QWCusJNdk30IZ","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:40:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kzYUeNS0mMCOmXEie35QWCusJNdk30IZ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:40:25 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:40:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-17 11:40:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-17 11:40:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:25 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-17 11:40:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3227DF1D-62DA-41B7-BCBA-445AE86618B2 (syncValue: DAiCxukEq8UkOxAAqer7Vs7zAJ4IyrSK)'
,2017-07-17 11:40:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-17 11:40:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52401
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DAiCxukEq8UkOxAAqer7Vs7zAJ4IyrSK","error":null,"portNumber":52401}'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DAiCxukEq8UkOxAAqer7Vs7zAJ4IyrSK', error: 'null', listeningPort: '52401''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,ok 185 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) found active relay
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [6, 7, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gBTE9DBzssWyxJAvrJNNeCUSIRbK8tmb","error":null,"portNumber":52401}'
,ok 186 No error
,ok 187 Ports equal
,ok 188 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) found active relay
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WVZh825J127vX0erMxAZOpAhJvGsqXn0","error":null,"portNumber":52401}'
,ok 189 No error
,ok 190 Ports equal
,# teardown
,2017-07-17 11:40:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 ,11:40:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
,2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 191 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6396697D-E678-496B-A513-1569FA649E5E
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[Thali,Core] VirtualSocket.deinit vsID:8 [6, 7]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 192 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52401
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DAiCxukEq8UkOxAAqer7Vs7zAJ4IyrSK","error":"Session disconnected","portNumber":null}'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.deinit
,# initial peer discovery
,2017-07-17 11:40:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-17 11:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-17 11:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-17 11:40:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-17 11:40:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-17 11:40:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'listening 52404'
,ok 193 Should throw
,# teardown
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'listening 52406'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 194 initial connection state should be CONNECTED
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 195 final connection state should be DISCONNECTED
,# teardown
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'listening 52409'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 196 tried to connect to right port
,ok 197 failed due to refused connection
,ok 198 routerPortConnectionFailed is emitted
,# teardown
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'listening 52413'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 199 Send/recvd #1 should be equal length
,ok 200 Send/recvd #1 should be same
,ok 201 Send/recvd #2 should be equal length
,ok 202 Send/recvd #2 should be same
,ok 203 Should be exactly 2 client sockets
,# teardown
,2017-07-17 11:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client co,nnection to node - 0 - 0 - closed'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP cli,ent connection <-> Mux - 0 - close'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'listening 52418'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 204 socket shouldn't close until after stream
,ok 205 incoming remains open
,# teardown
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - close'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'listening 52422'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 206 we should not have gotten an error
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 207 socket shouldn't close until after incoming
,ok 208 incoming is cleaned up
,# teardown
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'listening 52426'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 209 stream was closed
,ok 210 incoming should survive
,ok 211 mux should have no streams
,# teardown
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - close'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'listening 52430'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 212 we should not have gotten an error
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 213 Buffers are identical
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 214 native server is nulled out
,ok 215 native server should be closed
,ok 216 incoming has been removed
,ok 217 Incoming should be done
,ok 218 The mux object should be closed
,ok 219 The mux stream should be closed
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'listening 52434'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 220 native server is nulled out
,ok 221 native server should be closed
,ok 222 incoming has been removed
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'listening 52486'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 223 we should not have gotten an error
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 224 Buffers are identical
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 225 server should be fine
,ok 226 server should be open
,ok 227 incoming has been removed
,ok 228 The mux object should be closed
,ok 229 The mux stream should be closed
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:36 - DEBUG createNativeListener: 'listening 52490'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 230 we should not have gotten an error
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 231 Buffers are identical
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 232 server should be fine
,ok 233 server should be open
,ok 234 incoming has been removed
,ok 235 The mux object should be closed
,ok 236 The mux stream should be closed
,# teardown
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 237 serversManager must not be null
ok 238 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 239 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:37 - DEBUG createNativeListener: 'listening 52493'
ok 240 port must be in range
,# teardown
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'listening 52494'
,ok 241 second start should return same port
,# teardown
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'listening 52496'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 242 we should be connected
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 243 now we are disconnected
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-17 11:40:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 244 Passed bogus id
,2017-07-17 11:40:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 245 Passed good id but bogus port
,2017-07-17 11:40:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 246 Passed right context
,ok 247 Right server
,ok 248 No error should be set
,ok 249 Retry should be false
,ok 250 We called close server
,# teardown
,# setup
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Single local http request
,listening on 52498
,ok 251 should be equal
,# teardown
,2017-07-17 11:40:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 252 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
,[ThaliCore] Browser.startListening
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-17 11:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 253 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","generation":0}'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3227DF1D-62DA-41B7-BCBA-445AE86618B2 (syncValue: zh53focTE81z2HUrHh1sMp5EdRNSXZFQ)'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "32,27DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
,2017-07-17 11:40:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":0}'
,2017-07-17 11:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
,2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":0}'
,2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:32,27DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:32,27DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317
[ThaliCore] Advertiser: session connected Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:32,27DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2 error: max retries exceeded
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zh53focTE81z2HUrHh1sMp5EdRNSXZFQ","error":"Connection could not be established","portNumber":null}'
2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zh53focTE81z2HUrHh1sMp5EdRNSXZFQ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'Received ,peer availability changed event with {"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A01F0780-5874-4132-B66C-844CF07ED48B (syncValue: pO37GMQ,QKuRJzu4otVlvm5r1fgYCT78O)'
2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A01F0780-5874,-4132-B66C-844CF07ED48B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
[ThaliCore] Advertiser: session connected Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52512
2017-07-17 11:40:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pO37GMQQKuRJzu4otVlvm5r1fgYCT78O",,"error":null,"portNumber":52512}'
2017-07-17 11:40:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pO37GMQQKuRJzu4otVlvm5r1fgYCT78O', error: 'null', listeningPort: '52512''
,ok 254 should be equal
,2017-07-17 11:40:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 138D52C4-835A-43F4-9A26-BD832DE1F30C (syncValue: o8KLrVo1Atnrop5v501bxGo1i2VDvUCO)'
,2017-07-17 11:40:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
,[ThaliCore] Session.session(_:peer:didChange:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52516
,2017-07-17 11:40:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"o8KLrVo1Atnrop5v501bxGo1i2VDvUCO","error":null,"portNumber":52516}'
,2017-07-17 11:40:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'o8KLrVo1Atnrop5v501bxGo1i2VDvUCO', error: 'null', listeningPort: '52516''
,ok 255 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:A01F0780-5874-4132-B66C-844CF07ED48B
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52512
[ThaliCore] TCPListener.socketDidD,isconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
,[ThaliCore] Session.deinit peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:138D52C4-835A-43F4-9A26-BD832DE1F30C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCP,Listener.stopListeningForConnectionsAndDisconnectClients() port:52516
[ThaliCore] Session.disconnect() peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListen,er.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
[ThaliCore] Sessio,n.session(_:peer:didChange:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
,2017-07-17 11:40:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"o8KLrVo1Atnrop5v501bxGo1i2VDvUCO","error":"Session disconnected","portNumber":null}'
,2017-07-17 11:40:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple local http requests
,listening on 52518
,ok 256 should be equal
,ok 257 should be equal
,ok 258 should be equal
,# teardown
,2017-07-17 11:40:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:40:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 259 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 260 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
,2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}'
,2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A01F0780-5874-4132-B66C-844CF07ED48B (syncValue: 80xhkOMqVwraKME9VrLYxFwU27M1evR1)'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
,2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}'
,2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317
[ThaliCore] Advertiser: session connected Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
[ThaliCore] Advertiser: session connected Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52525
2017-07-17 11:40:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"80xhkOMqVwraKME9VrLYxFwU27M1evR1",,"error":null,"portNumber":52525}'
2017-07-17 11:40:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '80xhkOMqVwraKME9VrLYxFwU27M1evR1', error: 'null', listeningPort: '52525''
,ok 261 should be equal
ok 262 should be equal
,ok 263 should be equal
,2017-07-17 11:40:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 138D52C4-835A-43F4-9A26-BD832DE1F30C (syncValue: RtportlPa3b2Mi7nh6lA8jjN3aJmoipY)'
,2017-07-17 11:40:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
,[ThaliCore] Session.session(_:peer:didChange:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52531
,2017-07-17 11:40:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RtportlPa3b2Mi7nh6lA8jjN3aJmoipY","error":null,"portNumber":52531}'
,2017-07-17 11:40:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RtportlPa3b2Mi7nh6lA8jjN3aJmoipY', error: 'null', listeningPort: '52531''
,ok 264 should be equal
,ok 265 should be equal
,ok 266 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:A01F0780-5874-4132-B66C-844CF07ED48B
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52525
[ThaliCore] Session.disconnect() peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
,[ThaliCore] Session.deinit peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:138D52C4-835A-43F4-9A26-BD832DE1F30C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52531
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
,[ThaliCore] Session.deinit peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
,[ThaliCore] BrowserRelay.deinit
,2017-07-17 11:40:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 267 specific error should be returned
,# teardown
,ok 268 must be stopped
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 269 specific error should be returned
,# teardown
,ok 270 must be stopped
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'listening 52535'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 271 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5
[ThaliCore] Advertiser.stopAdvertising() peerID:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 273 must be stopped
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'listening 52536'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:71AC87CE-8190-41DB-9072-7D8F6289DCD0
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 275 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:41:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-17 11:41:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'listening 52537'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "235BAC13-2DAE-4B5C-9823-C80ED32005F2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:235BAC13-2DAE-4B5C-9823-C80ED32005F2
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:41:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 277 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "235BAC13-2DAE-4B5C-9823-C80ED32005F2", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:235BAC13-2DAE-4B5C-9823-C80ED32005F2
2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:41:02, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 278 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:235BAC13-2DAE-4B5C-9823-C80ED32005F2
[ThaliCore] Advertiser.stopAdvertising() peerID:235BAC13-2DAE-4B5C-9823-C80ED32005F2
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-17 11:41:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 279 must be stopped
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'listening 52540'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 280 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 281 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 282 must be stopped
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 283 network status should have certain non-empty properties
,# teardown
,ok 284 must be stopped
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-17 11:41:03 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 285 specific error expected
,# teardown
,ok 286 must be stopped
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'listening 52541'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8B880D5F-679D-41C1-B5FB-5E05E899317B
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C051C220-24DB-4F66-A240-D6B80B0F6EF4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C051C220-24DB-4F66-A240-D6B80B0F6EF4
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 287 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C051C220-24DB-4F66-A240-D6B80B0F6EF4
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-17 11:41:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 288 must be stopped
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'listening 52544'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D5665186-5064-44D2-9441-29754A514732
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "587D18DE-8CCF-4C71-BC6D-F497A50AF51A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:587D18DE-8CCF-4C71-BC6D-F497A50AF51A
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:0,
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
,ok 289 TCP Servers Manager doesn't exists
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":0}]'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":0}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":0}]'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":0}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}]'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}]'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:587D18DE-8CCF-4C71-BC6D-F497A50AF51A
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 290 must be stopped
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'listening 52546'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:073A6685-04C9-49CA-93A7-0A38401C6202
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1B5575B4-EE42-4A32-974A-F230563168CF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1B5575B4-EE42-4A32-974A-F230563168CF
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1B5575B4-EE42-4A32-974A-F230563168CF
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 291 is stopped after calling stop
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":0}]'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":0}'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 292 connection should fail after stopping
,# teardown
,ok 293 must be stopped
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-17 11:41:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 294 must be stopped
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 295 error description matches
,# teardown
,ok 296 must be stopped
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-17 11:41:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 297 must be stopped
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 298 error description matches
,# teardown
,ok 299 must be stopped
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 300 IMPLEMENT ME!!!!!!
,# teardown
,ok 301 must be stopped
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-17 11:41:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 302 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-17 11:41:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 303 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-17 11:41:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 304 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-17 11:41:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 305 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 306 NOT IMPLEMENTED # SKIP
,# teardown
,ok 307 must be stopped
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-17 11:41:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 308 must be stopped
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-17 11:41:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 309 must be stopped
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-17 11:41:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 310 must be stopped
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-17 11:41:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 311 must be stopped
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'listening 52549'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E72C57E2-2BC1-4A48-8AF1-FF9F13E280F4
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 312 discoveryActive matches
ok 313 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 314 discoveryActive matches
ok 315 advertisingActive matches
,2017-07-17 11:41:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'listening 52550'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D4A8937-3F33-4E9C-86C2-924E657A1929", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4D4A8937-3F33-4E9C-86C2-924E657A1929
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 316 discoveryActive matches
,ok 317 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:4D4A8937-3F33-4E9C-86C2-924E657A1929
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 318 discoveryActive matches
,ok 319 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'listening 52552'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:10 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-17 11:41:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 320 must be stopped
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'listening 52553'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CAB9C751-9093-419B-9269-317FAFAAB716
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6B833D50-0F9F-437B-A9E0-D2582037231A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6B833D50-0F9F-437B-A9E0-D2582037231A
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:41:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:143BC745-1F91-4BA2-A049-76A23351B43F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}]'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}]'
2017-07-17 11:41:11 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}'
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native, layer [{"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":0}]'
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A01F0780-5,874-4132-B66C-844CF07ED48B","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1119AE2-6CED-48C1-9D20-CA6950622AA0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":1,"portNumber":null}'
ok 321 portNumber equal null
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}]'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:6B833D50-0F9F-437B-A9E0-D2582037231A
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 must be stopped
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'listening 52555'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CFA99B50-8672-43BB-8DA1-7303D9DB0A47
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DDA978C1-76A0-4186-8090-EFD75BD499F8
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:143BC745-1F91-4BA2-A049-76A23351B43F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
2017-07-17 11:41:12 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-,4132-B66C-844CF07ED48B", generation: 1)
2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}'
[ThaliCore] Browse,r.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1119AE2-6CED-48C1-9D20-CA6950622AA0:0
2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A01F0780-5,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
874-4132-B66C-844CF07ED48B","generation":1}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66,C-844CF07ED48B:0
2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}'
[ThaliCore] BrowserManager.foundPeerHandl,er peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}]'
2017-07-17 11:41:12 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":0}]'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":0}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 143BC745-1F91-4BA2-A049-76A23351B43F (syncValue: DqDdZgPS825qpO6G9UtHbd7cttyAaF21)'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:143BC745-1F91-4BA2-A049-76A23351B43F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":1,"portNumber":null}'
2017-07-17 11:41:12 - DEBUG thaliMob,ileNativeTestUtils: 'We got a peer {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:143BC745-1F91-4BA2-A049-76A23351B43F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0)
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}]'
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-17 11:41:13 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C1119AE2-6CED-48C1-9D20-CA6950622AA0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIden,tifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:942,4ABB4-619A-4022-A320-5F9F8BA181B7:0
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}'
[ThaliCore] BrowserMa,nager.foundPeerHandler peer:Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:46D0B3B1-9593-4088-AF16-D54D985A55CD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "46D0B3B1-9593-4088-AF16-D54D985A55CD", generation: 0)
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}]'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","generation":0}]'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","generation":0}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:143BC745-1F91-4BA2-A049-76A23351B43F:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "14,3BC745-1F91-4BA2-A049-76A23351B43F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DqDdZgPS825qpO6G9UtHbd7cttyAaF21","error":"Peer is unavailable",,"portNumber":null}'
2017-07-17 11:41:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DqDdZgPS825qpO6G9UtHbd7cttyAaF21', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-17 11:41:13 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-17 11:41:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:143BC745-1F91-4BA2-A049-76A23351B43F
,2017-07-17 11:41:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A01F0780-5874-4132-B66C-844CF07ED48B (syncValue: 7HJFVcOUz9BZ61D3XZ7S4knapzvRi7p8)'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1119AE2-6CED-48C1-9D20-CA6950622AA0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
,2017-07-17 11:41:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}]'
,2017-07-17 11:41:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}'
,2017-07-17 11:41:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A0,1F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,01F0780-5874-4132-B66C-844CF07ED48B", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C1119AE2-6CED-48C1-9D20-CA6950622AA0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
,2017-07-17 11:41:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}]'
,2017-07-17 11:41:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}'
,2017-07-17 11:41:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-17 11:41:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.deinit peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A0,1F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,01F0780-5874-4132-B66C-844CF07ED48B", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A0,1F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,01F0780-5874-4132-B66C-844CF07ED48B", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F563BF1A-3AB9-432A-AAC9-4FCD08AFC6E9
[ThaliCore] Advertiser: session connected Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F563BF1A-3AB9-432A-AAC9-4FCD08AFC6E9 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}]'
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}'
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-17 11:41:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: notConnected -> notConnected
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:A01F0780-5874-4132-B66C-844CF07ED48B error: ma,x retries exceeded
,2017-07-17 11:41:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7HJFVcOUz9BZ61D3XZ7S4knapzvRi7p8","error":"Connection could not be established","portNumber":null}'
,2017-07-17 11:41:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7HJFVcOUz9BZ61D3XZ7S4knapzvRi7p8', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-17 11:41:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:A01F0780-5874-4132-B66C-844CF07ED48B
,2017-07-17 11:41:18 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-17 11:41:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9424ABB4-619A-4022-A320-5F9F8BA181B7 (syncValue: 0KW7MCxGWCzRHXtLaE5OWuXTT0lLcnf8)'
,2017-07-17 11:41:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F563BF1A-3AB9-432A-AAC9-4FCD08AFC6E9
,[ThaliCore] Session.session(_:peer:didChange:) peer:F563BF1A-3AB9-432A-AAC9-4FCD08AFC6E9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F563BF1A-3AB9-432A-AAC9-4FCD08AFC6E9
[ThaliCore] Session.startOutputStream(with:) peer:F563BF1A-3AB9-432A-AAC9-4FCD08AFC6E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [6, 7, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52571
,2017-07-17 11:41:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0KW7MCxGWCzRHXtLaE5OWuXTT0lLcnf8","error":null,"portNumber":52571}'
,2017-07-17 11:41:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0KW7MCxGWCzRHXtLaE5OWuXTT0lLcnf8', error: 'null', listeningPort: '52571''
,2017-07-17 11:41:21 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [6, 7, 9, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-17 11:41:21 - DEBUG testUtils: 'Got response data'
,2017-07-17 11:41:21 - DEBUG testUtils: 'Got end'
,ok 323 response body should match testData
,ok 324 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DDA978C1-76A0-4186-8090-EFD75BD499F8
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:41:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-17 11:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-17 11:41:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 325 must be stopped
[ThaliCore] B,rowserManager.disconnect peer:9424ABB4-619A-4022-A320-5F9F8BA181B7
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSL,ocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients(,) port:52571
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:9
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didCloseVirtua,lSocketStreamsHandler state:disconnecting
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] Session.disconnect() peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] TCPListener.deinit
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:10 [6, 7, 9]
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [6, 7]
,[ThaliCore] Session.session(_:peer:didChange:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0KW7MCxGWCzRHXtLaE5OWuXTT0lLcnf8","error":"Session disconnected","portNumber":null}'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:F563BF1A-3AB9-432A-AAC9-4FCD08AFC6E9 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F563BF1A-3AB9-432A-AAC9-4FCD08AFC6E9
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:F563BF1A-3AB9-432A-AAC9-4FCD08AFC6E9
,# can still do HTTP requests between peers with coordinator
,2017-07-17 11:41:24 - DEBUG thaliMobileNativeWrapper: 'listening 52573'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:027C6EEA-7FF8-4C41-8901-71E7E29D5622
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "58223822-23C2-4AFC-A05A-9BEDE692E47A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:58223822-23C2-4AFC-A05A-9BEDE692E47A
,2017-07-17 11:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
2017-07-17 11:41:25 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}]'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}'
,2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9424ABB4-619A-4022-A320-5F9F8BA181B,7 (syncValue: bYypzcSaQbL6lSX7fDfzTvDI97sSZsnr)'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8B,A181B7", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0)
2017-07-17 11:41:26 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"304D8B74-5781-4F43-ACB7-9345FE1C4478","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F357,2614-3152-45C7-97AC-98014F29C3FB:0
2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"304D8B74-5781-4F43-ACB7-9345FE1C4478","generation":0}'
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "F3572614-3152-45C7-97AC-98014F29C3FB", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58223822-23C2-4AFC-A05A-9BEDE692E47A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Pee,r(uuid: "58223822-23C2-4AFC-A05A-9BEDE692E47A", generation: 0)
2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"304D8B74-5781-4F43-ACB7-9345FE1C4478","peerAvailable":true,"generation":0,"po,rtNumber":null}'
,2017-07-17 11:41:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"304D8B74-5781-4F43-ACB7-9345FE1C4478","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"304D8B74-5781-4F43-ACB7-9345FE1C4478","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F3572614-3152-45C7-97AC-98014F29C3FB","generation":0}]'
2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F3572614-3152-45C7-97AC-98014F29C3FB","generation":0}'
,2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F3572614-3152-45C7-97AC-98014F29C3FB","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:26 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F3572614-3152-45C7-97AC-98014F29C3FB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F3572614-3152-45C7-97AC-98014F29C3FB","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
,[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:94,24ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:94,24ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:94,24ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9424ABB4,-619A-4022-A320-5F9F8BA181B7 error: max retries exceeded
2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bYypzcSaQbL6lSX7fDfzTvDI97sSZsnr","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:41:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bYypzcSaQbL6lSX7fDfzTvDI97sSZsnr', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 304D8B74-5781-4F43-ACB7-9345FE1C4478 (syncValue: 0k53WHFDpD7BtVaYjVTkF4FYwXQtrUb2)'
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52589
2017-07-17 11:41:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0k53WHFDpD7BtVaYjVTkF4FYwXQtrUb2",,"error":null,"portNumber":52589}'
2017-07-17 11:41:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0k53WHFDpD7BtVaYjVTkF4FYwXQtrUb2', error: 'null', listeningPort: '52589''
,2017-07-17 11:41:32 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [6, 7, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-17 11:41:32 - DEBUG testUtils: 'Got response data'
,2017-07-17 11:41:32 - DEBUG testUtils: 'Got end'
,ok 326 response body should match testData
,ok 327 must be started
,# teardown
,2017-07-17 11:41:33 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-17 11:41:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:41:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:41:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
2017-07-17 11:41:52 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}]'
2017-07-17 11:41:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}'
,2017-07-17 11:41:52 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-17 11:41:52 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-17 11:41:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4,D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4,D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-17 11:42:32 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - can still do HTTP requests between peers with coordinator, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/10AF6D81-932,4-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/blu,ebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-17 11:42:32 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-17 11:42:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4,D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4,D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4,D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4,D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4,D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4,D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D5,4-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/10AF6D81-9324-4D54-9174-82044A5706A7/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
