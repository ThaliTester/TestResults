#### Test 14182954130f6dc3_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/14182954130f6dc3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/28EDE62D-FFC0-4440-BB9C-098BB66974E8/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/28EDE62D-FFC0-4440-BB9C-098BB66974E8/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/14182954130f6dc3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/14182954130f6dc3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62706"
,(lldb)     command script import "/tmp/28EDE62D-FFC0-4440-BB9C-098BB66974E8/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,JXcore Cordova bridge is ready
JXcore engine is started
,2017-09-19 12:46:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:46:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:46:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:46:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:46:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:46:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:46:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A73342E3-9A1B-4B27-A64D-4145A6EDED00", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A73342E3-9A1B-4B27-A64D-4145A6EDED00
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E4311C53-0CFE-40EA-8F7B-E615942259E0
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C00243F7-,F0CE-4604-B90F-B6B90258A118
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AB1FEAC6-81E3-4202-88BF-BB6475140470", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:AB1FEAC6-81E3-4202-88BF-BB6475140470
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AB1FEAC6-81E3-4202-88BF-BB6475140470:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AB1FEAC6-81E3-4202-88BF-BB6475140470", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-09-19 12:46:12 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.816697120666504
,2017-09-19 12:46:12 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-09-19 12:46:12 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:AB1FEAC6-81E3-4202-88BF-BB6475140470:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "AB1FEAC6-81E3-4202-88BF-BB6475140470", generation: 0)
,2017-09-19 12:46:15 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-09-19 12:46:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-09-19 12:46:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-09-19 12:46:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-09-19 12:46:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-09-19 12:46:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-09-19 12:46:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-09-19 12:46:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-09-19 12:46:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-09-19 12:46:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-09-19 12:46:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-09-19 12:46:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-09-19 12:46:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-09-19 12:46:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-09-19 12:46:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-09-19 12:46:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-09-19 12:46:19 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,2017-09-19 12:46:19 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-09-19 12:46:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F,9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F,9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F,9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F,9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F,9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F,9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:47:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F,9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:47:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:47:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F,9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:47:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/192EE227-AECB-44F9-AAA7-8C4FEC6AF524/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:47:27 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-09-19 12:47:27 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-09-19 12:47:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-09-19 12:47:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-09-19 12:47:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-09-19 12:47:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
2017-09-19 12:47:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-09-19 12:47:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-09-19 12:47:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-09-19 12:47:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
ok 11 should be equal
ok 12 should be equal
,ok 13 should be equal
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
,2017-09-19 12:48:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-09-19 12:48:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-09-19 12:48:16 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-09-19 12:48:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-09-19 12:48:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5C4FC68A-6F71-481D-943E-1B634DAD24D5
[ThaliCore] Browser.startListening
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:22 - INFO tha,l,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5675969C-9068-4B2B-8682-B8EA8A201DCE
[ThaliCore] Browser.startListening
2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-09-19 12:48:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:48:23 - INFO thaliMobile: 'Received state ({"discoveryA,c,tive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:48:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "67FD06D2-5509-47D2-9E94-A63B5788F122", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:67FD06D2-5509-47D2-9E94-A63B5788F122
2017-09-19 1,2:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:67FD06D2-5509-47D2-9E94-A63B5788F122
2017-09-19 12:48:28 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C847A0DB-53AD-4FE1-97DC-C9CFA8E48D4C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C847A0DB-53AD-4FE1-97DC-C9CFA8E48D4C
2017-09-19 1,2:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C847A0DB-53AD-4FE1-97DC-C9CFA8E48D4C", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:C847A0DB-53AD-4FE1-97DC-C9CFA8E48D4C
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C847A0DB-53AD-4FE1-97DC-C9CFA8E48D4C
,[ThaliCore] Advertiser.stopAdvertising() peerID:C847A0DB-53AD-4FE1-97DC-C9CFA8E48D4C
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8C630424-8DA2-471A-94E5-D7030EA7C764
2017-09-19 1,2:48:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F7795BCB-BFAA-4776-8AA9-4DD8C8CFBCD8
[Thali,Core] Browser.startListening
2017-09-19 12:48:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:48:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:30 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8C630424-8DA2-471A-94E5-D7030EA7C764:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90D276E0-9265-451E-B424-F09E6598D6BE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90D276E0-9265-451E-B424-F09E6598D6BE", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F99EF8B7-1AD6-4A8B-9090-EC705C6AD918:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8C630424-8DA2-471A-94E5-D7030EA7C764
2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:396621D0-FC75-4B94-8457-AEC9F0E309BF
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:48:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:29346E8E-E1A2-49B6-896F-074F68A5135A
[ThaliCore] Browser.startListening
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:48:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F99EF8B7-1AD6-4A8B-9090-EC705C6AD918:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", generation: 0)
,2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F99EF8B7-1AD6-4A8B-9090-EC705C6AD918","generation":0}'
,2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F99EF8B7-1AD6-4A8B-9090-EC705C6AD918 (syncValue: mXeMqqGJ6wU8FQLh7WzeHysoJwe7ZjRF)'
,2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F99EF8B7-1AD6-4A8B-9090-EC705C6AD918:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
,2017-09-19 12:48:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9FE7713F-E1CA-49E3-8F90-9C5C97270C09","generation":0}'
,2017-09-19 12:48:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
2017-09-19 12:48:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DF13A8A5-46A4-4EA6-9302-580CEBBE797A","generation":0}'
2017-09-19 12:48:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:34 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:48:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F99EF8B7-1AD6-4A8B-9090-EC705C6AD918:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F99EF8B7-1AD6-4A8B-9090-EC705C6AD918:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F9,9EF8B7-1AD6-4A8B-9090-EC705C6AD918:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", ,generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FB5AF2C2-F5C6-4A74-BC34-07703243569D
[ThaliCore] Advertiser: session connected Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FB5AF2C2-F5C6-4A74-BC34-07703243569D state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-09-19 12:48:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mXeMqqGJ6wU8FQLh7WzeHysoJwe7ZjRF","error":"Peer is unavailable","portNumber":null}'
2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mXeMqqGJ6wU8FQLh7WzeHysoJwe7ZjRF', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:48:36 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9FE7713F-E1CA-49E3-8F90-9C5C97270C09 (syncValue: HfyV3zjnfjijXZHb01wJGrKy8rJKQWFY)'
,2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F99EF8B7-1AD6-4A8B-9090-EC705C6AD918:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FB5AF2C2-F5C6-4A74-BC34-07703243569D
,[ThaliCore] Session.session(_:peer:didChange:) peer:FB5AF2C2-F5C6-4A74-BC34-07703243569D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61079
,2017-09-19 12:48:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HfyV3zjnfjijXZHb01wJGrKy8rJKQWFY","error":null,"portNumber":61079}'
,2017-09-19 12:48:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HfyV3zjnfjijXZHb01wJGrKy8rJKQWFY', error: 'null', listeningPort: '61079''
,2017-09-19 12:48:39 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-09-19 12:48:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:48:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:48:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:396621D0-FC75-4B94-8457-AEC9F0E309BF
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FB5AF2C2-F5C6-4A74-BC34-07703243569D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61079
[ThaliCore] TCPClient.deinit
,[ThaliCore] Session.disconnect() peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:FB5AF2C2-F5C6-4A74-BC34-07703243569D
,[ThaliCore] TCPListener.deinit
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
,[ThaliCore] BrowserRelay.deinit
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:48:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:FB5AF2C2-F5C6-4A74-BC34-07703243569D
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FDB7528A-6D5A-476F-989F-0B13DC545963
2017-09-19 1,2:48:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C9FA9FBD-592F-44A9-BCC8-99C3A66B2463
,[ThaliCore] Browser.startListening
,2017-09-19 12:48:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:48:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-09-19 12:48:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
2017-09-19 12:48:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9FE7713F-E1CA-49E3-8F90-9C5C97270C09","generation":0}'
2017-09-19 12:48:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9FE7713F-E1CA-49E3-8F90-9C5C97270C09, (syncValue: zBQNl0OqyOszEcJt2kA5uQQ9EVFo6xuv)'
2017-09-19 12:48:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C972,70C09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9FE7713F-E1CA-49E3-8F9,0-9C5C97270C09:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DF13A8A5-46A4-4EA6-9302-580CEBBE797A","generation":0}'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE","generation":0}'
2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
2017-09-19 12:48:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C","generation":0}'
2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:42 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,E7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4BDC289B-F8E1-4389-85C8-925084ABFFE5
[ThaliCore] Advertiser: session connected Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4BDC289B-F8E1-4389-85C8-925084ABFFE5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,E7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4BDC289B-F8E1-4389-85C8-925084ABFFE5
,[ThaliCore] Session.session(_:peer:didChange:) peer:4BDC289B-F8E1-4389-85C8-925084ABFFE5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4BDC289B-F8E1-4389-85C8-925084ABFFE5
[ThaliCore] Session.startOutputStream(with:) peer:4BDC289B-F8E1-4389-85C8-925084ABFFE5
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-09-19 12:48:47 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-09-19 12:48:47 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-09-19 12:48:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-09-19 12:48:47 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,E7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,E7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9FE7713F,-E1CA-49E3-8F90-9C5C97270C09 error: max retries exceeded
2017-09-19 12:48:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zBQNl0OqyOszEcJt2kA5uQQ9EVFo6xuv","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:48:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zBQNl0OqyOszEcJt2kA5uQQ9EVFo6xuv', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:48:52 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-09-19 12:48:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE (syncValue: cV6U9JK,VUeLiGp9KNuAw3e3tJsdJFOKN)'
2017-09-19 12:48:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:79AF77E4-D3C7,-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:48:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61087
2017-09-19 12:48:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cV6U9JKVUeLiGp9KNuAw3e3tJsdJFOKN",,"error":null,"portNumber":61087}'
2017-09-19 12:48:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cV6U9JKVUeLiGp9KNuAw3e3tJsdJFOKN', error: 'null', listeningPort: '61087''
,Connecting to the localhost:61087
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
,Connected to the localhost:61087
,2017-09-19 12:48:54 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-09-19 12:48:54 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
ok 88 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C70C581A-6F96-4146-A741-09B345570AC6
[ThaliCore] Advertiser: session connected Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C70C581A-6F96-4146-A741-09B345570AC6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C70C581A-6F96-4146-A741-09B345570AC6
,[ThaliCore] Session.session(_:peer:didChange:) peer:C70C581A-6F96-4146-A741-09B345570AC6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C70C581A-6F96-4146-A741-09B345570AC6
,[ThaliCore] Session.startOutputStream(with:) peer:C70C581A-6F96-4146-A741-09B345570AC6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 3]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-09-19 12:48:59 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-09-19 12:48:59 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-09-19 12:48:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-09-19 12:48:59 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [1]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-09-19 12:48:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:48:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:FDB7528A-6D5A-476F-989F-0B13DC545963
,[ThaliCore] Session.session(_:peer:didChange:) peer:C70C581A-6F96-4146-A741-09B345570AC6 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C70C581A-6F96-4146-A741-09B345570AC6
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61087
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cV6U9JKVUeLiGp9KNuAw3e3tJsdJFOKN","error":"Session disconnected","portNumber":null}'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:C70C581A-6F96-4146-A741-09B345570AC6
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:09FDF337-6845-4807-9835-1630B55E626D
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F338BE61-6F8A-4688-B675-EE08105E092D
[ThaliCore] Browser.startListening
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:48:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
[ThaliCore] Session.session(_:peer:didChange:) peer:4BDC289B-F8E1-4389-85C8-925084ABFFE5 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE","generation":0}'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE (syncValue: ox8KgftGBX5nFECtVRaWSeLfaPcrhpSI)'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C","generation":0}'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
2017-09-19 12:49:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FA542401-F573-4621-9DBD-9F1F61CD325C","generation":0}'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPe,er:withDiscoveryInfo:) found peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4FF4D8AD-7583-4E46-A0AE-07975F33B677","generation":0}'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:79,AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,9AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:79,AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,9AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:79,AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,9AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:79,AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:79AF77E4,-D3C7-4DFF-9AFD-79675AC9E4DE error: max retries exceeded
2017-09-19 12:49:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ox8KgftGBX5nFECtVRaWSeLfaPcrhpSI","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:49:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ox8KgftGBX5nFECtVRaWSeLfaPcrhpSI', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:49:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-09-19 12:49:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FA542401-F573-4621-9DBD-9F1F61CD325C (syncValue: l7lzvvj,ckDBWZfXYObhlrtLTTCTmEw1n)'
2017-09-19 12:49:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FA542401-F573,-4621-9DBD-9F1F61CD325C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:11 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t!'
2017-09-19 12:49:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61104
2017-09-19 12:49:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"l7lzvvjckDBWZfXYObhlrtLTTCTmEw1n",,"error":null,"portNumber":61104}'
2017-09-19 12:49:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'l7lzvvjckDBWZfXYObhlrtLTTCTmEw1n', error: 'null', listeningPort: '61104''
Connecting to the localhost:61104
Connecting to th,e localhost:61104
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
Connecting to the localhost:61104
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] Session.startOutputStream(with:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,Connected to the localhost:61104
,Connected to the localhost:61104
Connected to the localhost:61104
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [5, 6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [5]
,ok 96 got the same data back
,# teardown
,2017-09-19 12:49:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 ,12:49:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-09-19 12:49:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:09FDF337-6845-4807-9835-1630B55E626D
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:49:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:FA542401-F573-4621-9DBD-9F1F61CD325C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61104
[ThaliCore] Session.disconnect() p,eer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:49:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:62C3A3CE-D25E-4073-8C66-B8F9673DB39F
,2017-09-19 12:49:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:49:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:49:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A6DCB927-B503-4348-B86E-9F8AB59D69D3
,[ThaliCore] Browser.startListening
,2017-09-19 12:49:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:49:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:49:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
2017-09-19 12:49:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE","generation":0}'
2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE, (syncValue: rDuyw5i9i4CGJ9MsZcSt5TsllAHlApFO)'
2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC,9E4DE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"4FF4D8AD-7583-4E46-A0AE-07975F33B677","generation":0}'
2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C58D711-31E1-42BB-A9B7-C41E6294A0FD","generation":0}'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B224C079-0793-4C1D-8FF3-899E71D44BAD","generation":0}'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:79,AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,9AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:49:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rDuyw5i9i4CGJ9MsZcSt5TsllAHlApFO","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:49:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rDuyw5i9i4CGJ9MsZcSt5TsllAHlApFO', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:49:21 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:49:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4FF4D8AD-7583-4E46-A0AE-07975F33B677 (syncValue: tzuhL7v0w3QQQFw95RMMLf6,k2zvWbnnL)'
2017-09-19 12:49:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4FF4D8AD-7583-4E46-A0AE-07975,F33B677:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 ,12:49:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4F,F4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:49:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tzuhL7v0w3QQQFw95RMMLf6k2zvWbnnL","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:49:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tzuhL7v0w3QQQFw95RMMLf6k2zvWbnnL', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:49:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:49:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C58D711-31E1-42BB-A9B7-C41E6294A0FD (syncValue: mQCYqaHNsf09ImWkczrSPfY,SnxfiHO0S)'
2017-09-19 12:49:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C58D711-31E1-42BB-A9B7-C41E6,294A0FD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61117
,2017-09-19 12:49:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mQCYqaHNsf09ImWkczrSPfYSnxfiHO0S","error":null,"portNumber":61117}'
,2017-09-19 12:49:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mQCYqaHNsf09ImWkczrSPfYSnxfiHO0S', error: 'null', listeningPort: '61117''
,Connecting to the localhost:61117
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [5, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:61117
,2017-09-19 12:49:27 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-09-19 12:49:28 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [5]
,# teardown
,2017-09-19 12:49:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:49:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:49:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:62C3A3CE-D25E-4073-8C66-B8F9673DB39F
2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12,:49:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61117
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:49:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mQCYqaHNsf09ImWkczrSPfYSnxfiHO0S","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:49A00F14-0EB2-468A-A004-75D2B5F0AF5F
,2017-09-19 12:49:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:49:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:49:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5948F9C4-AC6D-444D-952C-D956A54DAE22
[ThaliCore] Browser.startListening
,2017-09-19 12:49:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:49:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:49:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
2017-09-19 12:49:35 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B224C079-0793-4C1D-8FF3-899E71D44BAD","generation":0}'
2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B224C079-0793-4C1D-8FF3-899E71D44BAD, (syncValue: 4GkLjMqilQEf8RyczE03LTyN3l6BsOYg)'
,2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B2,24C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C58D711-31E1-42BB-A9B7-C41E6294A0FD","generation":0}'
2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
,2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5B0178B6-A741-4E00-AC62-1F9897244011","generation":0}'
2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
2017-09-19 12:49:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"865FCB1B-7BD8-4406-B2FB-599546BA3E60","generation":0}'
2017-09-19 12:49:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:36 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:49:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B2,24C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B2,24C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B2,24C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B2,24C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B224C079,-0793-4C1D-8FF3-899E71D44BAD error: max retries exceeded
2017-09-19 12:49:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4GkLjMqilQEf8RyczE03LTyN3l6BsOYg","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:49:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4GkLjMqilQEf8RyczE03LTyN3l6BsOYg', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:49:46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-09-19 12:49:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C58D711-31E1-42BB-A9B7-C41E6294A0FD (syncValue: Fw4r7Lk,DfxwooAtfXQI8cCvvtFIdtFuA)'
2017-09-19 12:49:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C58D711-31E1,-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:49:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:49:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Fw4r7LkDfxwooAtfXQI8cCvvtFIdtFuA","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:49:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Fw4r7LkDfxwooAtfXQI8cCvvtFIdtFuA', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:49:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:49:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5B0178B6-A741-4E00-AC62-1F9897244011 (syncValue: U8WtNr5IKYgcEnIOkJeCXyhcU2Wzm2cG)'
,2017-09-19 12:49:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:49:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FAF8EBD4-6611-4629-918B-9346A00412D1
[ThaliCore] Advertiser: session connected Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FAF8EBD4-6611-4629-918B-9346A00412D1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61135
,2017-09-19 12:49:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"U8WtNr5IKYgcEnIOkJeCXyhcU2Wzm2cG","error":null,"portNumber":61135}'
,2017-09-19 12:49:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'U8WtNr5IKYgcEnIOkJeCXyhcU2Wzm2cG', error: 'null', listeningPort: '61135''
,Connecting to the localhost:61135
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,Connected to the localhost:61135
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [5, 8]
2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:8
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [5]
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FAF8EBD4-6611-4629-918B-9346A00412D1
,[ThaliCore] Session.session(_:peer:didChange:) peer:FAF8EBD4-6611-4629-918B-9346A00412D1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FAF8EBD4-6611-4629-918B-9346A00412D1
[ThaliCore] Session.startOutputStream(with:) peer:FAF8EBD4-6611-4629-918B-9346A00412D1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [5, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (13140 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (10240 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (5516 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (6428 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (4522 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received (5311 bytes):'
,2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-09-19 12:50:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:50:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:49A00F14-0EB2-468A-A004-75D2B5F0AF5F
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:5B0178B6-A741-4E00-AC62-1F9897244011
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61135
[ThaliCore] Session.disconnect() peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,[ThaliCore] BrowserRelay.deinit
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:FAF8EBD4-6611-4629-918B-9346A00412D1 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] Adve,rtiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:FAF8EBD4-6611-4629-918B-9346A00412D1
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:FAF8EBD4-6611-4629-918B-9346A00412D1
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4770B320-808D-4E5D-89AE-D95AEC921D53
[ThaliCore] Browser.startListening
2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:50:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "06803A25-E8DE-4A6B-8E67-EF7F618CC7F4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:06803A25-E8DE-4A6B-8E67-EF7F618CC7F4
2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:50:00 ,- INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType,":null}})'
2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
2017-09-19 12:50:01 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"865FCB1B-7BD8-4406-B2FB-599546BA3E60","generation":0}]'
2017-09-19 12:50:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"865FCB1B-7BD8-4406-B2FB-599546BA3E60","generation":0}'
2017-09-19 12:50:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
,2017-09-19 12:50:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5B0178B6-A741-4E00-AC62-1F9897244011","generation":0}]'
,2017-09-19 12:50:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5B0178B6-A741-4E00-AC62-1F9897244011","generation":0}'
,2017-09-19 12:50:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
,2017-09-19 12:50:02 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B","generation":0}]'
,2017-09-19 12:50:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B","generation":0}'
,2017-09-19 12:50:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06803A25-E8DE-4A6B-8E67-EF7F618CC7F4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06803A25-E8DE-4A6B-8E67-EF7F618CC7F4", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 ,12:50:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:06803A25-E8DE-4A6B-8E67-E,F7F618CC7F4
2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-09-19 12:50:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6425B525-5961-4012-AD31-28CE9459B039
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F639401F-EEAC-486B-831F-EEEEA3F327BA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F639401F-EEAC-486B-831F-EEEEA3F327BA
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F639401F-EEAC-486B-831F-EEEEA3F327BA
,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:08 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-09-19 12:50:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-09-19 12:50:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-09-19 12:50:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
,2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-09-19 12:50:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-09-19 12:50:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-09-19 12:50:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:c65f0ee9-2f81-4190-a464-e56ee94b9f37 error: startListeningNotActive
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"TUmLODOQc6KVKPZhTCdyUzvuxPIC5Iu1","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort ,is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:970CFBF3-62B2-45BC-A326-022D504C7594
,[ThaliCore] Browser.startListening
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:50:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
ok 131 No error on starting
,ok 132 Got null as expected
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eJGcPJaejhdixlKQ1JQ2plgMN5HjOqFM","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
,# teardown
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"865FCB1B-7BD8-4406-B2FB-599546BA3E60","generation":0}]'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"865FCB1B-7BD8-4406-B2FB-599546BA3E60","generation":0}'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5B0178B6-A741-4E00-AC62-1F9897244011","generation":0}]'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5B0178B6-A741-4E00-AC62-1F9897244011","generation":0}'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-09-19 12:50:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:622317CD-BD51-4215-A582-1BE55CA12534
[ThaliCore] Browser.startListening
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:50:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on star,ting
,ok 138 Got right error
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"865FCB1B-7BD8-4406-B2FB-599546BA3E60","generation":0}]'
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"865FCB1B-7BD8-4406-B2FB-599546BA3E60","generation":0}'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"pe,erAvailable":true,"peerIdentifier":"5B0178B6-A741-4E00-AC62-1F9897244011","generation":0}]'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5B0178B6-A741-4E00-AC62-1F9897244011","generation":0}'
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Filt,ered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:4f838328-1f2b-417d-bc88-ba3ad7c9c222
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CE085BEC-A868-440D-8066-CAEC5CC0BC19
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:50:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:77E48F85-45CD-4AEB-91C5-FB154B207EFB
[ThaliCore] Browser.startListening
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:50:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:50:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"865FCB1B-7BD8-4406-B2FB-599546BA3E60","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 865FCB1B-7BD8-4406-B2FB-599546BA3E60 (syncValue: Uzxkkjt0naQyVp87iowiWhvTZgHLbD8p)'
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "86,5FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5B0178B6-A741-4E00-AC62-1F9897244011","generation":0}'
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
,2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5","generation":0}'
2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
2017-09-19 12:50:16 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E205BA54-258E-4F38-8E64-D5B41A94C652","generation":0}'
2017-09-19 12:50:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:50:16 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:50:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:50:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:86,5FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,65FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:5B0178B6-A741-4E00-AC62-1F9897244011:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:86,5FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,65FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:50:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Uzxkkjt0naQyVp87iowiWhvTZgHLbD8p","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:50:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Uzxkkjt0naQyVp87iowiWhvTZgHLbD8p', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:50:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:50:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5 (syncValue: 5cKTkY7ixpf9GyWHLuxeUFo,nrWPt94iw)'
2017-09-19 12:50:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ABA4A2E6-AFBB-41B6-96A9-4F406,5A734F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:50:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C9A9E26D-98D4-40A7-9875-ED34C32DF968
[ThaliCore] Advertiser: session connected Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C9A9E26D-98D4-40A7-9875-ED34C32DF968 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61148
2017-09-19 12:50:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5cKTkY7ixpf9GyWHLuxeUFonrWPt94iw","error":null,"portNumber":61148}'
2017-09-19 12:50:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5cKTkY7ixpf9GyWHLuxeUFonrWPt94iw', error: 'null', listeningPort: '61148''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
,ok 143 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0) found active relay
2017-09-19 12:50:22 - DEBUG thaliMobileNativeWrapper: 'multiConn,ectResolved: {"syncValue":"KPGsX1AoJiRlQpL9xl9XUDdwVmin6nb7","error":null,"portNumber":61148}'
ok 144 No error
ok 145 Ports equal
ok 146 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ABA4A,2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0) found active relay
2017-09-19 12:50:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BhAPjwi6mSk0IDaopyaZt0hG3xpEd0pS","error":null,"portNumber":61148}'
ok 147 No error
,ok 148 Ports equal
# teardown
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [5, 9, 10]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C9A9E26D-98D4-40A7-9875-ED34C32DF968
,[ThaliCore] Session.session(_:peer:didChange:) peer:C9A9E26D-98D4-40A7-9875-ED34C32DF968 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C9A9E26D-98D4-40A7-9875-ED34C32DF968
,[ThaliCore] Session.startOutputStream(with:) peer:C9A9E26D-98D4-40A7-9875-ED34C32DF968
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [5, 9, 10, 11]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0ACFC213-8950-4D40-94AC-F4B1F01D6330
[ThaliCore] Advertiser: session connected Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0ACFC213-8950-4D40-94AC-F4B1F01D6330 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0ACFC213-8950-4D40-94AC-F4B1F01D6330
,[ThaliCore] Session.session(_:peer:didChange:) peer:0ACFC213-8950-4D40-94AC-F4B1F01D6330 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ACFC213-8950-4D40-94AC-F4B1F01D6330
[ThaliCore] Session.startOutputStream(with:) peer:0ACFC213-8950-4D40-94AC-F4B1F01D6330
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [5, 9, 10, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-09-19 12:50:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 ,12:50:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-09-19 12:50:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CE085BEC-A868-440D-8066-C,AEC5CC0BC19
2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Option,al(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
2017-09-19 12:50:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).',
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisco,nnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:11,
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserManager.disconnect peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61148
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDi,sconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:11 [5, 9, 10, 12]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [5, 9, 10]
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:10 [5, 9]
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0ACFC213-8950-4D40-94AC-F4B1F01D6330 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0ACFC213-8950-4D40-94AC-F4B1F01D6330
,# setup
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5cKTkY7ixpf9GyWHLuxeUFonrWPt94iw","error":"Session disconnected","portNumber":null}'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:0ACFC213-8950-4D40-94AC-F4B1F01D6330
,[ThaliCore] Session.session(_:peer:didChange:) peer:C9A9E26D-98D4-40A7-9875-ED34C32DF968 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
,# initial peer discovery
,2017-09-19 12:50:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-09-19 12:50:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-09-19 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-09-19 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-09-19 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-09-19 12:50:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'listening 61153'
,ok 149 Should throw
,# teardown
,2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:42 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'listening 61155'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'listening 61158'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'listening 61162'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'listening 61167'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'listening 61171'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'listening 61175'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'listening 61179'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-09-19 12:50:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'listening 61183'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-09-19 12:50:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-09-19 12:50:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'listening 61235'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'listening 61239'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-09-19 12:50:48 - DEBUG createNativeListener: 'listening 61242'
ok 196 port must be in range
,# teardown
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'listening 61243'
,ok 197 second start should return same port
,# teardown
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'listening 61245'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-09-19 12:50:49 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-09-19 12:50:49 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-09-19 12:50:49 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 61247
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:39C6DE90-E027-43EA-AFED-DFDEEFC4A256
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:50:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:351ED129-3C30-4A7C-BD3B-BB068A992D61
[ThaliCore] Browser.startListening
2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
2017-09-19 12:50:49 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"E205BA54-258E-4F38-8E64-D5B41A94C652","generation":0}'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E205BA54-258E-4F38-8E64-D5B41A94C652 (syncValue: STacnaxyczD729CgrXkP6dX8YYhSCYu1)'
2017-09-19 12:50:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2,05BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:50:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5","generation":0}'
2017-09-19 12:50:49 - DEBU,G thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:50:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7","generation":0}'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D","generation":0}'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E2,05BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E2,05BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E2,05BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E2,05BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:E205BA54,-258E-4F38-8E64-D5B41A94C652 error: max retries exceeded
2017-09-19 12:51:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"STacnaxyczD729CgrXkP6dX8YYhSCYu1","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:51:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'STacnaxyczD729CgrXkP6dX8YYhSCYu1', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:51:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-09-19 12:51:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7 (syncValue: 3l8LS4v,LO6HzWnDyydz8mCy9Wsqmk6la)'
2017-09-19 12:51:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFA49C3E-B67B,-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:51:00 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-09-19 12:51:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BAF145EB-1C51-4367-A988-16E703F33D45
[ThaliCore] Advertiser: session connected Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BAF145EB-1C51-4367-A988-16E703F33D45 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28
[ThaliCore] Session.session(_:peer:didChange:) peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61261
,2017-09-19 12:51:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3l8LS4vLO6HzWnDyydz8mCy9Wsqmk6la","error":null,"portNumber":61261}'
,2017-09-19 12:51:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3l8LS4vLO6HzWnDyydz8mCy9Wsqmk6la', error: 'null', listeningPort: '61261''
,ok 210 should be equal
,2017-09-19 12:51:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D (syncValue: rE7wb2SNDHxyJc2bCLnTF7oM4Fs7tk2N)'
,2017-09-19 12:51:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-09-19 12:51:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28
,[ThaliCore] Session.session(_:peer:didChange:) peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BAF145EB-1C51-4367-A988-16E703F33D45
,[ThaliCore] Session.session(_:peer:didChange:) peer:BAF145EB-1C51-4367-A988-16E703F33D45 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61265
2017-09-19 12:51:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rE7wb2SNDHxyJc2bCLnTF7oM4Fs7tk2N",,"error":null,"portNumber":61265}'
2017-09-19 12:51:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rE7wb2SNDHxyJc2bCLnTF7oM4Fs7tk2N', error: 'null', listeningPort: '61265''
,ok 211 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 ,12:51:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-09-19 12:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:39C6DE90-E027-43EA-AFED-D,FDEEFC4A256
2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
[ThaliCore] BrowserManager.disconnect peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61261
[ThaliCore] Sess,ion.disconnect() peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61265
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28 state: connected -> notConnected
,[ThaliCore] Session.session(_:peer:didChange:) peer:BAF145EB-1C51-4367-A988-16E703F33D45 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] Advertise,r: session notConnected Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnec,tNonTCPSession()
[ThaliCore] Session.disconnect() peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28
,[ThaliCore] Session.deinit peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
,[ThaliCore] BrowserRelay.deinit
,2017-09-19 12:51:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28
,# Multiple local http requests
,listening on 61267
,ok 212 should be equal
ok 213 should be equal
ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:09 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:51:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:73CFC2FD-1259-4083-9C92-2E89F1043EE6
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:51:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 215 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C48D091A-B372-4B1C-989A-DB4C536041F1
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:51:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
2017-09-19 12:51:10 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7 (syncValue: sYaVETwCRv3sf0AV3UwbDVYv56Kvzn8A)'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D","generation":0}'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","generation":0}'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:446E2367-C254-4409-9086-F5ED433913DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
2017-09-19 12:51:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","generation":0}'
2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:51:11 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,A49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,FA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,A49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,FA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,A49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,FA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,A49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:CFA49C3E,-B67B-4D77-BF0D-298E8ACE5DF7 error: max retries exceeded
2017-09-19 12:51:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sYaVETwCRv3sf0AV3UwbDVYv56Kvzn8A","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:51:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sYaVETwCRv3sf0AV3UwbDVYv56Kvzn8A', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:51:21 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-09-19 12:51:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 37F90D9D-C502-4429-B6AC-531362636BBF (syncValue: 0ObxAHK,KCycGzho0PYSbGEpVncfRGfXh)'
2017-09-19 12:51:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:37F90D9D-C502,-4429-B6AC-531362636BBF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:37F90D9D-C502-4429-B6AC-531362636BBF:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9
[ThaliCore] Advertiser: session connected Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:37F90D9D-C502-4429-B6AC-531362636BBF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61285
,2017-09-19 12:51:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0ObxAHKKCycGzho0PYSbGEpVncfRGfXh","error":null,"portNumber":61285}'
,2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0ObxAHKKCycGzho0PYSbGEpVncfRGfXh', error: 'null', listeningPort: '61285''
,ok 217 should be equal
ok 218 should be equal
ok 219 should be equal
,2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 446E2367-C254-4409-9086-F5ED433913DB (syncValue: RhIl8UXa89X7V43JDpEp4pUahSyvlPD0)'
,2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:446E2367-C254-4409-9086-F5ED433913DB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:446E2367-C254-4409-9086-F5ED433913DB:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD
[ThaliCore] Session.session(_:peer:didChange:) peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:446E2367-C254-4409-9086-F5ED433913DB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:446E2367-C254-4409-9086-F5ED433913DB:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61292
,2017-09-19 12:51:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RhIl8UXa89X7V43JDpEp4pUahSyvlPD0","error":null,"portNumber":61292}'
,2017-09-19 12:51:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RhIl8UXa89X7V43JDpEp4pUahSyvlPD0', error: 'null', listeningPort: '61292''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD
,[ThaliCore] Session.session(_:peer:didChange:) peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:51:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 ,12:51:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:73CFC2FD-1259-4083-9C92-2,E89F1043EE6
2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] Session.session(_:peer:didChange:) peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[Tha,liCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD
,[ThaliCore] BrowserManager.disconnect peer:37F90D9D-C502-4429-B6AC-531362636BBF
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61285
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:37F90D9D-C502-4429-B6AC-531362636BBF:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:446E2367-C254-4409-9086-F5ED433913DB
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61292
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:446E2367-C254-4409-9086-F5ED433913DB:0
,[ThaliCore] Session.deinit peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:446E2367-C254-4409-9086-F5ED433913DB:0
[ThaliCore] BrowserRelay.deinit
,2017-09-19 12:51:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0ObxAHKKCycGzho0PYSbGEpVncfRGfXh","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'listening 61296'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:51:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'listening 61297'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A3F078DD-60FE-4E24-8FDA-DAE30134CADD
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'listening 61298'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "36CD9CC1-A2FE-438D-89C8-5AD9E0E6D5FA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:36CD9CC1-A2FE-438D-89C8-5AD9E0E6D5FA
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 233 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "36CD9CC1-A2FE-438D-89C8-5AD9E0E6D5FA", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:36CD9CC1-A2FE-438D-89C8-5AD9E0E6D5FA
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:36CD9CC1-A2FE-438D-89C8-5AD9E0E6D5FA
,[ThaliCore] Advertiser.stopAdvertising() peerID:36CD9CC1-A2FE-438D-89C8-5AD9E0E6D5FA
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:33 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:51:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'listening 61301'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:34 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-09-19 12:51:34 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:34 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'listening 61302'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4AE32F34-B1F4-495C-957C-B71DDB9ECF0A
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4A49304E-10DF-4FB5-B140-CA9EE2FCCDF5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4A49304E-10DF-4FB5-B140-CA9EE2FCCDF5
2017-09-19 1,2:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4A49304E-10DF-4FB5-B140-CA9EE2FCCDF5
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-09-19 12:51:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'listening 61305'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:22E458C4-1A4A-4F6A-8517-67A44C22D487
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A5316604-5753-4FF2-970A-52211C64047B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A5316604-5753-4FF2-970A-52211C64047B
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:A5316604-5753-4FF2-970A-52211C64047B
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'listening 61307'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E28EBBE7-A7D1-4B6D-A835-8BF9E4D3A934
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "96B2A737-B5A2-4572-B65C-748102B473AC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:96B2A737-B5A2-4572-B65C-748102B473AC
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:96B2A737-B5A2-4572-B65C-748102B473AC
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-09-19 12:51:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-09-19 12:51:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-09-19 12:51:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:38 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-09-19 12:51:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-09-19 12:51:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-09-19 12:51:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:39 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-09-19 12:51:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-09-19 12:51:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:40 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-09-19 12:51:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-09-19 12:51:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'listening 61310'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4DF9403C-BACB-42A0-B28A-4EB88D51BAEA
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
,ok 271 advertisingActive matches
2017-09-19 12:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'listening 61311'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "80F99E94-9586-413E-A2D4-7BA602ADAF06", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:80F99E94-9586-413E-A2D4-7BA602ADAF06
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 272 discoveryActive matches
ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:80F99E94-9586-413E-A2D4-7BA602ADAF06
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
ok 275 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'listening 61313'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'listening 61314'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6734895B-BD56-4BBC-9240-47042DB30090
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:51:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:1EB74B74-2182-4EF8-AB06-C62817FE919E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1EB74B74-2182-4EF8-AB06-C62817FE919E", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:446E2367-C254-4409-9086-F5ED433913DB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","generation":0}]'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","generation":0}'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","generation":0}]'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","generation":0}'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","generation":0}]'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","generation":0}'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 277 portNumber equal null
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BAD17115-B3D7-4616-834B-02D88C9985D3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BAD17115-B3D7-4616-834B-02D88C9985D3", generation: 0)
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","generation":0}]'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","generation":0}'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'listening 61316'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:500CB1B8-9B95-4BF9-BACD-7BD262FE2D4C
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:573C5C14-23ED-405D-B676-0A82D053A509
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:51:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1EB74B74-2182-4EF8-AB06-C62817FE919E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1EB74B74-2182-4EF8-AB06-C62817FE919E", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:446E2367-C254-4409-9086-F5ED433913DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BAD17115-B3D7-4616-834B-02D88C998,5D3:0
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Pee,r(uuid: "BAD17115-B3D7-4616-834B-02D88C9985D3", generation: 0)
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E",",generation":0}]'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","generation":0}'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","generation":0}]'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","generation":0}]'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 37F90D9D-C502-4429-B6AC-531362636BBF (syncValue: sLDKMNfFRrfPy8PrfXsw6FfC6NXMjkGR)'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1EB74B74-2182-4EF8-AB06-C62817FE919E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1EB74B74-2182-4EF8-AB06-C62817FE919E", generation: 0)
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","generation":0}]'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BAD17115-B3D7-4616-834B-02D88C9985D3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BAD17115-B3D7-4616-834B-02D88C9985D3", generation: 0)
2017-09-19 12:51:45 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","generation":0}]'
2017-09-19 12:51:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:11F98CCD-AF7B-421E-ACC2-2EBC279ED663:0
[ThaliCore] BrowserManager.foundPeerHandle,r peer:Peer(uuid: "11F98CCD-AF7B-421E-ACC2-2EBC279ED663", generation: 0)
,2017-09-19 12:51:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","peerAvailable":false,"generation":null,"portNumber":null}'
2017-09-19 12:51:45 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:573C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
,2017-09-19 12:51:45 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"11F98CCD-AF7B-421E-ACC2-2EBC279ED663","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:C1D0148D-6FD3-48E7-B035-B4E113A88E98:0
2017-09-19 12:51:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"11F98CCD-AF7B-421E-ACC2-2EBC279ED663","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1D0148D-6FD3-48E7-B035-B4E113A88E98", generation: 0)
,2017-09-19 12:51:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"11F98CCD-AF7B-421E-ACC2-2EBC279ED663","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"11F98CCD-AF7B-421E-ACC2-2EBC279ED663","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-09-19 12:51:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"11F98CCD-AF7B-421E-ACC2-2EBC279ED663","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:45 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1D0148D-6FD3-48E7-B035-B4E113A88E98","generation":0}]'
,2017-09-19 12:51:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C1D0148D-6FD3-48E7-B035-B4E113A88E98","generation":0}'
,2017-09-19 12:51:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1D0148D-6FD3-48E7-B035-B4E113A88E98","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1D0148D-6FD3-48E7-B035-B4E113A88E98","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-09-19 12:51:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C1D0148D-6FD3-48E7-B035-B4E113A88E98","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:37F90D9D-C502-4429-B6AC-531362636BBF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:37,F90D9D-C502-4429-B6AC-531362636BBF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,7F90D9D-C502-4429-B6AC-531362636BBF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","generation":0}]'
2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","generation":0}'
,2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","peerAvailable":false,"generation":null,"portNumber":null}'
2017-09-19 12:51:47 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:37F90D9D-C502-4429-B6AC-531362636BBF:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:51:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sLDKMNfFRrfPy8PrfXsw6FfC6NXMjkGR","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:51:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sLDKMNfFRrfPy8PrfXsw6FfC6NXMjkGR', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:51:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-09-19 12:51:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 446E2367-C254-4409-9086-F5ED433913DB (syncValue: sWvWEgybT1q4s6xlKeI7ALnEljtVXXZb)'
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:446E2367-C254-4409-9086-F5ED433913DB:0,
2017-09-19 12:51:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "44,6E2367-C254-4409-9086-F5ED433913DB", generation: 0)
,[ThaliCore] Session.deinit peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-09-19 12:51:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sWvWEgybT1q4s6xlKeI7ALnEljtVXXZb","error":"Peer is unavailable","portNumber":null}'
,2017-09-19 12:51:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sWvWEgybT1q4s6xlKeI7ALnEljtVXXZb', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:51:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-09-19 12:51:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 11F98CCD-AF7B-421E-ACC2-2EBC279ED663 (syncValue: ePeGfOR8Hy5LQjawkWQ6pwvk9srxBFq5)'
,2017-09-19 12:51:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'

```
