#### Test 1322832571374948_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1322832571374948/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/919F5C7B-39C4-4F0B-87FF-2ED67E045AAE/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/919F5C7B-39C4-4F0B-87FF-2ED67E045AAE/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1322832571374948/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1322832571374948/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62468"
,(lldb)     command script import "/tmp/919F5C7B-39C4-4F0B-87FF-2ED67E045AAE/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,2017-07-26 15:24:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:24:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:24:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:24:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:24:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:24:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:24:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4F215D4D-EF89-4A82-A1,23-CCEAF07D1C75", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4F215D4D-EF89-4A82-A123-CCEAF07D1C75
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:883E8064-ECF5-4CA1-8300-D1BD8B5171E7
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A654C699-,712B-43DA-9FD5-1BC2E9890638
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "98C2E92C-215E-43B7-BF4D-6980885DBCBC", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:98C2E92C-215E-43B7-BF4D-6980885DBCBC
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:98C2E92C-215E-43B7-BF4D-6980885DBCBC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "98C2E92C-215E-43B7-BF4D-6980885DBCBC", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-26 15:24:31 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  1.488531947135925
,2017-07-26 15:24:31 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-07-26 15:24:31 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:98C2E92C-215E-43B7-BF4D-6980885DBCBC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "98C2E92C-215E-43B7-BF4D-6980885DBCBC", generation: 0)
,2017-07-26 15:24:34 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-26 15:24:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-26 15:24:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-26 15:24:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-26 15:24:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-26 15:24:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-26 15:24:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-26 15:24:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-26 15:24:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-26 15:24:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-26 15:24:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-26 15:24:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-26 15:24:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-26 15:24:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-26 15:24:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-26 15:24:38 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-26 15:24:38 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-26 15:24:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:25:06 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-07-26 15:25:06 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-26 15:25:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
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
# teardown
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
2017-07-26 15:25:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-26 15:25:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-26 15:25:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-26 15:25:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-26 15:25:42 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-26 15:25:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BD2B7EE5-AADE-4569-A375-A0DE3F174A44
[ThaliCore] Browser.startListening
2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-26 15:25:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8AE3AC0A-D2D2-4A52-BA2C-21C0ED581E0F
[ThaliCore] Browser.startListening
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-26 15:25:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-26 15:25:51 - INFO thaliMobile: 'Received state ({"discoveryA,c,tive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "336F7110-39F2-4ED5-8553-5ADD7F91D2F3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:336F7110-39F2-4ED5-8553-5ADD7F91D2F3
2017-07-26 1,5:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:336F7110-39F2-4ED5-8553-5ADD7F91D2F3
2017-07-26 15:25:53 - DEBUG tha,l,iMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AE379CB2-8F0B-482C-8AEF-72F5E6546CBF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AE379CB2-8F0B-482C-8AEF-72F5E6546CBF
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AE379CB2-8F0B-482C-8AEF-72F5E6546CBF", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:AE379CB2-8F0B-482C-8AEF-72F5E6546CBF
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:AE379CB2-8F0B-482C-8AEF-72F5E6546CBF
,[ThaliCore] Advertiser.stopAdvertising() peerID:AE379CB2-8F0B-482C-8AEF-72F5E6546CBF
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
2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7045561F-3AC7-42B2-AAA8-794CD97CD393", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7045561F-3AC7-42B2-AAA8-794CD97CD393
2017-07-26 15:25:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:25:55, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-26 15:25:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:4E1EFDA5-88B3-4337-990B-2D1A9F6C966F
[ThaliCore] Browser.startListening
2017-07-26 15:25:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,t,isingActive":true}'
,2017-07-26 15:25:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-26 15:25:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:65BB0631-4C8E-48D5-9C63-E15CC7BCBCC0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65BB0631-4C8E-48D5-9C63-E15CC7BCBCC0", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:7045561F-3AC7-42B2-AAA8-794CD97CD393:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7045561F-3AC7-42B2-AAA8-794CD97CD393", generation: 0)
ok 76 peers must be an array
ok 77 peers must not be zero,-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E0E1C65-B1BC-4465-8138-E2F4FF7F1002:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E0E1C65-B1BC-4465-8138-E2F4FF7F1002", generation,: 0)
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:25:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7045561F-3AC7-42B2-AAA8-794CD97CD393
2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:81834FD2-2B19-4DA1-8940-C11D8697ADB7
2017-07-26 1,5:26:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:26:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-26 15:26:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAd,vertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D145E406-7804-4762-BB2C-5DCF327D3263
[ThaliCore] Browser.startListening
2017-07-26 15:26:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":true,"advertisingActive":true}'
2017-07-26 15:26:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,rtArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24", generation: 0)
2017-07-26 15:26:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1972DBD3-7860-483F-83A6-386F04A64800","generation":0}'
,2017-07-26 15:26:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1972DBD3-7860-483F-83A6-386F04A64800 (syncValue: PYaepqhe2e0syXEmhpcM6r403IWxahXw)'
,2017-07-26 15:26:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:26:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"233EEF45-D37B-4C1F-B455-6684C2646D24","generation":0}'
,2017-07-26 15:26:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63508
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PYaepqhe2e0syXEmhpcM6r403IWxahXw","error":null,"portNumber":63508}'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PYaepqhe2e0syXEmhpcM6r403IWxahXw', error: 'null', listeningPort: '63508''
,2017-07-26 15:26:08 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-26 15:26:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 ,15:26:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-26 15:26:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:81834FD2-2B19-4DA1-8940-C,11D8697ADB7
2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:26:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:1972DBD3-7860-483F-83A6-386F04A64800
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63508
[ThaliCore] Session.disconnect() peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserRelay.deinit
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:26:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CC3FF4E7-6553-4363-AEA7-645E14A53DDD
2017-07-26 1,5:26:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EAFC77EB-9012-4E06-A073-32941282816D
[Thal,iCore] Browser.startListening
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:26:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24", generation: 0)
2017-07-26 15:26:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1972DBD3-7860-483F-83A6-386F04A64800","generation":0}'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1972DBD3-7860-483F-83A6-386F04A64800 (syncValue: aDZipZizhpNxxWKEOHd14ZD7xwp2hGnr)'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"233EEF45-D37B-4C1F-B455-6684C2646D24","generation":0}'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A","generation":0}'
2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
2017-07-26 15:26:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"96F9B2E1-4E94-4042-B264-425C9D00CBDB","generation":0}'
2017-07-26 15:26:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:11 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:26:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:19,72DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,972DBD3-7860-483F-83A6-386F04A64800", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:19,72DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,972DBD3-7860-483F-83A6-386F04A64800", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:19,72DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,972DBD3-7860-483F-83A6-386F04A64800", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1972DBD3-7860-483F-83A6-386F04A64800:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1972DBD3,-7860-483F-83A6-386F04A64800 error: max retries exceeded
2017-07-26 15:26:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aDZipZizhpNxxWKEOHd14ZD7xwp2hGnr","error":"Connection could not be established","portNumber":null}'
2017-0,7-26 15:26:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'aDZipZizhpNxxWKEOHd14ZD7xwp2hGnr', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-26 15:26:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-26 15:26:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A (syncValue: 65FxRIO,2kKggsRvHw0C8Y6RKoQ3FXqCY)'
2017-07-26 15:26:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ADEF5EDA-671B,-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:26:20 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-07-26 15:26:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:26726993-A74D-48FD-BA87-4EA1294BD300
[ThaliCore] Advertiser: session connected Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:26726993-A74D-48FD-BA87-4EA1294BD300 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63515
2017-07-26 15:26:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"65FxRIO2kKggsRvHw0C8Y6RKoQ3FXqCY",,"error":null,"portNumber":63515}'
2017-07-26 15:26:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '65FxRIO2kKggsRvHw0C8Y6RKoQ3FXqCY', error: 'null', listeningPort: '63515''
Connecting to the localhost:63515
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
,Connected to the localhost:63515
,2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:26726993-A74D-48FD-BA87-4EA1294BD300
,[ThaliCore] Session.session(_:peer:didChange:) peer:26726993-A74D-48FD-BA87-4EA1294BD300 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26726993-A74D-48FD-BA87-4EA1294BD300
[ThaliCore] Session.startOutputStream(with:) peer:26726993-A74D-48FD-BA87-4EA1294BD300
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-26 15:26:24 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-26 15:26:24 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-26 15:26:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-26 15:26:24 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client discon,nected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-26 15:26:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CC3FF4E7-6553-4363-AEA7-645E14A53DDD
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63515
[ThaliCore] Session.disconnect() p,eer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:26726993-A74D-48FD-BA87-4EA1294BD300 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:26726993-A74D-48FD-BA87-4EA1294BD300
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E
2017-07-26 1,5:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AC695C71-4915-470A-B373-90291BEF1320
[Thal,iCore] Browser.startListening
2017-07-26 15:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:26:25 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:26726993-A74D-48FD-BA87-4EA1294BD300
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
2017-07-26 15:26:26 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A (syncValue: ajgKaQmL9lbAmettg59OhcPZcl28c1qO)'
2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"96F9B2E1-4E94-4042-B264-425C9D00CBDB","generation":0}'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
2017-07-26 15:26:27 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CEA74DD1-9E19-42C5-827A-AEC245524BBC","generation":0}'
2017-07-26 15:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:27 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
,2017-07-26 15:26:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4E65AFCB-31AE-4C2A-AB9E-05D327D66222","generation":0}'
2017-07-26 15:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,EF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,DEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,EF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,DEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,EF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,DEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,EF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:ADEF5EDA,-671B-4553-A56D-9B5DA5C16E3A error: max retries exceeded
2017-07-26 15:26:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ajgKaQmL9lbAmettg59OhcPZcl28c1qO","error":"Connection could not be established","portNumber":null}'
2017-0,7-26 15:26:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ajgKaQmL9lbAmettg59OhcPZcl28c1qO', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-26 15:26:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-26 15:26:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 96F9B2E1-4E94-4042-B264-425C9D00CBDB (syncValue: X1fje9L,UQa0zKrucZbWeNjHavJ0jFxYf)'
2017-07-26 15:26:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:96F9B2E1-4E94,-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:26:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD
[ThaliCore] Advertiser: session connected Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:96,F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,6F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-26 15:26:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"X1fje9LUQa0zKrucZbWeNjHavJ0jFxYf","error":"Peer is unavailable",,"portNumber":null}'
2017-07-26 15:26:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'X1fje9LUQa0zKrucZbWeNjHavJ0jFxYf', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-26 15:26:39 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-26 15:26:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CEA74DD1-9E19-42C5-827A-AEC245524BBC (syncValue: XnCClxQUqlU1dTV8zHUsoTP,5Ghsj6W2z)'
2017-07-26 15:26:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CEA74DD1-9E19-42C5-827A-AEC24,5524BBC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:26:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 ,1,5:26:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD
,[ThaliCore] Session.session(_:peer:didChange:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD
,[ThaliCore] Session.startOutputStream(with:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD
[ThaliCore] Session.startOutputStream(with:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD
[ThaliCore] Session.startOutputStream(with:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:peer:didChange:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0 state: notConnected -> connecting
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server received (13140 bytes):'
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server received all data: nFH1dm9PtPOSRSsQuWdj2SsDwa8UhMPMVaSmdHEoIjDd4EeRMgeYEowyTXN8jWQSYuh5fl6hAgplxG2TAR2Iv60hA8xtqhjAuSRgRFq2S23DgdjskXVxF4S1v9oNxfIjXu2Qk7QmFtBPEO198MlBxjMSUz7neW2FFaKAT9mx7w0nhkvcCR,XMVPQysUVD1CxhZheZrs7v1esiL4ac8vKHF3qziwTlxcg8iLmW5TEl0tHtocxAIjQ5iYYOHIdIeIdLfTWcba7wG23CqLaDmOYLV7ldYeiObvhS62ZnLhgK8lqWE9ilPOmyzIlkaFvsWU29vWP2FgcSzewBRM9MgUTXn23okJfMeKUidp4orx9pyhAS2AqwilgfUKzKMGcSn20kafbGOmaE4ug7PjFgr1qsX0JYH39xXPh0FMJtQusMDPfR4liKYr,kZQhkwBhpeIDthr1NgTYX4Rkua8Df9vhLUBe4t3xVD8oPCt5ENaJEe6QAN3OSqlOsshyKSZojRw9If4B1ENzGXemeWTl2nWvcVi3vc6j43stWRzD2EiGhYRD9XrUGhuQEnI71j7rWHKq2FWIp5BNK2697KTpPSpUwpw6Jso5KthhzMMSSPjDn53h252qXJkazKRXXCGAuUqIqr1YMU7YMcAlMLyuCZ79tidG1G5aF6G6154xqnM1Mr55FaUm2sEt,FN7T8B9Bf0hxNtW681V0Qn2p1wOaX27FLHPvXbIrAzXBCjnmwUnJNVErbcJ007ZBs1eVfKzDMUqTt0Pv6IIO2rf1zjZMGPLYIqTC7u4uaQxLVegLA6WqpZQlvuVJ1oxdPmIx93FJRxpp1TyfSwh7xIssAYvCAz5QMnUhQCr7vFBE8DFkjRb8GfzDNIVtO20aHtoOqF4oB6sjG6FI9H2GVz8Q8JBAf1bAtiTbU5JH72rxcCDmYapY1ZSBBp4gIsA8,NAlG55ZhWJuNnvxwdxXTmqtiHJ8HLwrWKalVSApYf3G1RhgO5qHtoupIhqri8zHx0Vgr4n2CtDvwNJbvjJIWBXyCk2WTCSVir3V1TtgimkQqaqi6KRzqmgrhztstOR5lTuSHvaz200MkGG3GadllQyDdTdEVC5PwSeC0uDTDzqKoD0efTGmYLDTcAFD3pqsbO7weBHttn3ACrxPtWI0bsJBKKU4OnvJ3GMmfOkN9yMYfKAse2OHGOAFtXwOxjQ8G,sfIlCwwSM9KO9y7aOgCE73rkBfXXiysSt4QuoDiJ6402gB1WnBFlzQIUgGJ3UwrJTz0XatRJIaHzBQTm3fsrfdsvNzqgRFr34I7y31ZNzqti6QPuwrYyw6cfcPA4qob28bo52Nt83QilosF7bfhQgrka4TwjGcGdQxmLWDoaDQuW1gsTvr5oeeaqgtFndTSkBU1wJEx4aeALNBzU9mnRQjXGifRZPFvBEg2KlN2iwQgzaqpRb2kPSaXErrHqWbDG,zXhsK15Y3qO6uA4tefQGeo8t0AS0wZp29KvBLdTlzi1WHdU5OmJVJzg4Ndbh13PJChD2t03BChJRRJykbHupLGhbHA6bvmrTzT50kIMkSetFnYixU7mu3GpEaNrYblPYy1EAqvjd0keVHlBjMGDa9lr9766dR3Cl1DsO3rsIXBJXqCBJxoMlVnef210PagVbGde2Zsm4S5AF4H9ZctVxpiMUzSH3JVWkZFyqCIhLRFYEhPbcqbucpmsgOtGdcMuP,ehQ5BSeoBJ9xrNGPZ70tW8hsLoh2qxSaRfrHHkbwapyQnrJ3ZMVRM87k5oRTkmL1tq5qRXSQHc8xX4LMTjUuT7eOiXfAVb2QM2QklC2IvcYKUYCjstWFTeJn35yQYVuupmca3FLENTU0DaaPpVEdpKdwgLOPT3NKGNNSqGZAJ2fH7jAc30AL8DjurFXnEezA8lwb16nOL3PmgNUnPF4OAuR9WRCqaHm3FKbE7KwjBtyQJUnbfMwRiuUOMIWUoxV1,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
Fu9lGb7sL,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'
2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [3, 5]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63537
,2017-07-26 15:26:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XnCClxQUqlU1dTV8zHUsoTP5Ghsj6W2z","error":null,"portNumber":63537}'
2017-07-26 15:26:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XnCClxQUqlU1dTV8zHUsoTP5Ghsj6W2z', error: 'null', listeningPort: '63537''
,Connecting to the localhost:63537
Connecting to the localhost:63537
Connecting to the localhost:63537
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
Connected to the localhost:63537
Connected to the localhost:63537
Connected to the localhost:63537
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [3, 5, 6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [3, 5, 6, 7, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [3, 5, 7, 8]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [3, 5, 8]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [3, 5]
,ok 96 got the same data back
,# teardown
,2017-07-26 15:26:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E
2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15,:,26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63537
,[ThaliCore] Session.disconnect() peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XnCClxQUqlU1dTV8zHUsoTP5Ghsj6W2z","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:909C9F79-A6F9-4BE4-8694-3AE62B5FD28A
[ThaliCore] Browser.startListening
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-26 15:26:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
2017-07-26 15:26:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4E65AFCB-31AE-4C2A-AB9E-05D327D66222","generation":0}'
2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4E65AFCB-31AE-4C2A-AB9E-05D327D66222, (syncValue: oPLNsk8PROx6Zvp7o21fkgFglUZTwKDh)'
2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D,66222", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
,2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CEA74DD1-9E19-42C5-827A-AEC245524BBC","generation":0}'
2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
2017-07-26 15:26:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ACCCCDA0-56FC-4073-BDCB-B144AD313CF5","generation":0}'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
2017-07-26 15:26:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1F9CF035-7C79-49E4-8780-3D74C1CE7552","generation":0}'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4E,65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4E,65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4E,65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4E,65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:4E65AFCB,-31AE-4C2A-AB9E-05D327D66222 error: max retries exceeded
2017-07-26 15:27:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oPLNsk8PROx6Zvp7o21fkgFglUZTwKDh","error":"Connection could not be established","portNumber":null}'
2017-0,7-26 15:27:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oPLNsk8PROx6Zvp7o21fkgFglUZTwKDh', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-26 15:27:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-26 15:27:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ACCCCDA0-56FC-4073-BDCB-B144AD313CF5 (syncValue: dgJGd5g,1DDZ6wc2sjjmmQCGVBDqpYAhL)'
2017-07-26 15:27:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ACCCCDA0-56FC,-4073-BDCB-B144AD313CF5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:27:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8B4002AF-5693-4A9C-8936-EBDF28F012EE
[ThaliCore] Advertiser: session connected Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8B4002AF-5693-4A9C-8936-EBDF28F012EE state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8B4002AF-5693-4A9C-8936-EBDF28F012EE
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B4002AF-5693-4A9C-8936-EBDF28F012EE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B4002AF-5693-4A9C-8936-EBDF28F012EE
[ThaliCore] Session.startOutputStream(with:) peer:8B4002AF-5693-4A9C-8936-EBDF28F012EE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [3, 5, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-26 15:27:04 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-26 15:27:04 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-26 15:27:04 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-26 15:27:04 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-26 15:27:04 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [3, 5]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63556
2017-07-26 15:27:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dgJGd5g1DDZ6wc2sjjmmQCGVBDqpYAhL","error":null,"portN,umber":63556}'
2017-07-26 15:27:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dgJGd5g1DDZ6wc2sjjmmQCGVBDqpYAhL', error: 'null', listeningPort: '63556''
,Connecting to the localhost:63556
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 5, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:63556
,2017-07-26 15:27:05 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-26 15:27:05 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,# teardown
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [3, 5]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3620668C-D9C3-430F-B6B7-3FBA900A10BE
[ThaliCore] Advertiser: session connected Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3620668C-D9C3-430F-B6B7-3FBA900A10BE state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3620668C-D9C3-430F-B6B7-3FBA900A10BE
,[ThaliCore] Session.session(_:peer:didChange:) peer:3620668C-D9C3-430F-B6B7-3FBA900A10BE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3620668C-D9C3-430F-B6B7-3FBA900A10BE
,[ThaliCore] Session.startOutputStream(with:) peer:3620668C-D9C3-430F-B6B7-3FBA900A10BE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 5, 11]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-26 15:27:11 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-26 15:27:11 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-26 15:27:11 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-26 15:27:11 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-26 15:27:11 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] Virt,ualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [3, 5]
,[ThaliCore] Session.session(_:peer:didChange:) peer:3620668C-D9C3-430F-B6B7-3FBA900A10BE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3620668C-D9C3-430F-B6B7-3FBA900A10BE
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:3620668C-D9C3-430F-B6B7-3FBA900A10BE
,2017-07-26 15:27:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:27:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-26 15:27:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63556
[ThaliCore] Session.disconnect() p,eer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-26 15:27:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dgJGd5g1DDZ6wc2sjjmmQCGVBDqpYAhL","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B4002AF-5693-4A9C-8936-EBDF28F012EE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
,[ThaliCore] Session.deinit peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
[ThaliCore] BrowserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:83EC259A-93F4-41CE-9EE5-01F8A89A9E61
,2017-07-26 15:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:27:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3EA1D45F-6560-40AE-83BD-505FC26AB9D4
,[ThaliCore] Browser.startListening
2017-07-26 15:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-26 15:27:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"1F9CF035-7C79-49E4-8780-3D74C1CE7552","generation":0}'
,2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1F9CF035-7C79-49E4-8780-3D74C1CE7552 (syncValue: Cm4RFaZxITGuTBJxZcQJD27ixEmfMpou)'
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ACCCCDA0-56FC-4073-BDCB-B144AD313CF5","generation":0}'
,2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
2017-07-26 15:27:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8FBD35BB-A103-436A-9CB9-3B7507AA53AB","generation":0}'
2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF9402D3-086D-4F63-9EE4-355E475E1C1F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF9402D3-086D-4F63-9EE4-355E475E1C1F", generation: 0)
,2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BF9402D3-086D-4F63-9EE4-355E475E1C1F","generation":0}'
,2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F884C464-2B85-430E-A2D4-FB4175AE796B
[ThaliCore] Advertiser: session connected Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F884C464-2B85-430E-A2D4-FB4175AE796B state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552 error: max retries exceeded
2017-07-26 15:27:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Cm4RFaZxITGuTBJxZcQJD27ixEmfMpou","error":"Connection could not be established","portNumber":null}'
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Cm4RFaZxITGuTBJxZcQJD27ixEmfMpou', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-26 15:27:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8FBD35BB-A103-436A-9CB9-3B7507AA53AB (syncValue: J1anq3i,ASkgZrkhkSUkCGxqupKA2h4mj)'
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8FBD35BB-A103,-436A-9CB9-3B7507AA53AB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F884C464-2B85-430E-A2D4-FB4175AE796B
,[ThaliCore] Session.session(_:peer:didChange:) peer:F884C464-2B85-430E-A2D4-FB4175AE796B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F884C464-2B85-430E-A2D4-FB4175AE796B
[ThaliCore] Session.startOutputStream(with:) peer:F884C464-2B85-430E-A2D4-FB4175AE796B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [3, 5, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63574
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (31684 bytes):'
,2017-07-26 15:27:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"J1anq3iASkgZrkhkSUkCGxqupKA2h4mj","error":null,"portNumber":63574}'
,2017-07-26 15:27:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'J1anq3iASkgZrkhkSUkCGxqupKA2h4mj', error: 'null', listeningPort: '63574''
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,Connecting to the localhost:63574
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,Connected to the localhost:63574
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [3, 5, 12, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:13 [3, 5, 12]
,ok 102 got the same data back
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (9691 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server data flushed',
# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [3, 5]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-26 15:27:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:27:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:83EC259A-93F4-41CE-9EE5-01F8A89A9E61
,[ThaliCore] Session.session(_:peer:didChange:) peer:F884C464-2B85-430E-A2D4-FB4175AE796B state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:F884C464-2B85-430E-A2D4-FB4175AE796B
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63574
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"J1anq3iASkgZrkhkSUkCGxqupKA2h4mj","error":"Session disconnected","portNumber":null}'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F8F300AB-91BA-4921-A4CF-1B06ECCA2F6F
,[ThaliCore] Browser.startListening
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-26 15:27:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F5E673DA-CC95-4DE6-A149-C189F65599D6
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-26 15:27:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Session.deinit peer:F884C464-2B85-430E-A2D4-FB4175AE796B
[ThaliCore] Session.deinit peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
2017-07-26 15:27:29 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8FBD35BB-A103-436A-9CB9-3B7507AA53AB","generation":0}]'
2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8FBD35BB-A103-436A-9CB9-3B7507AA53AB","generation":0}'
2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF9402D3-086D-4F63-9EE4-355E475E1C1F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF9402D3-086D-4F63-9EE4-355E475E1C1F", generation: 0)
2017-07-26 15:27:29 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BF9402D3-086D-4F63-9EE4-355E475E1C1F","generation":0}]'
2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"BF9402D3-086D-4F63-9EE4-355E475E1C1F","generation":0}'
2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BF9402D3-086D-4F63-9EE4-355E475E1C1F:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BF9402D3-086D-4F63-9EE4-355E475E1C1F", generation: 0)
,2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"BF9402D3-086D-4F63-9EE4-355E475E1C1F","generation":0}]'
2017-07-26 15:27:29 - DEBUG thaliMobileNative,Wrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"BF9402D3-086D-4F63-9EE4-355E475E1C1F","generation":0}'
2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent ,due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EF2B7C6-F5B1-4B26-8675-94DED121B6CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0)
,2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6EF2B7C6-F5B1-4B26-8675-94DED121B6CD","generation":0}]'
,2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6EF2B7C6-F5B1-4B26-8675-94DED121B6CD","generation":0}'
,2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
2017-07-26 15:27:31 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8FBD35BB-A103-436A-9CB9-3B7507AA53AB","generation":0}]'
2017-07-26 15:27:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"8FBD35BB-A103-436A-9CB9-3B7507AA53AB","generation":0}'
2017-07-26 15:27:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:27:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-26 15:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F5E673DA-CC95-4DE6-A149-C189F65599D6
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8E86C5A5-19BF-4AFF-A5C2-726FA7C5B910
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8316BACB-1278-400A-8B24-4B118A56BA3E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8316BACB-1278-400A-8B24-4B118A56BA3E
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:8316BACB-1278-400A-8B24-4B118A56BA3E
,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:34 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-26 15:27:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-26 15:27:35 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
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
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-26 15:27:35 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-26 15:27:35 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:36 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-26 15:27:36 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
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
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:841cd918-8d24-439f-a775-93d1dfe09970 error: startListeningNotActive
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PS8tWefDsOpaIaF3c2AnAeNGxMPcXdxJ","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:761B7E20-B9F8-4F31-A2C8-E09021629199
[ThaliCore] Browser.startListening
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-26 15:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CNXH4QxAX4YfW9Fk3HsMrAN4Md9i1jDy","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-26 15:27:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:37 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:07B4DDB8-F29F-47F1-98AC-5325BDCB0513
,[ThaliCore] Browser.startListening
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-26 15:27:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:d346b2fe-a85b-4cb9-9d5e-5a42e5a28d26
,ok 140 No error
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6C4BE094-B690-45C8-8D11-640C8096028F
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:27:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:626BD7C4-443D-4AE5-8DE1-709B880C531F
,[ThaliCore] Browser.startListening
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:27:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-26 15:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EF2B7C6-F5B1-4B26-8675-94DED121B6CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0)
2017-07-26 15:27:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6EF2B7C6-F5B1-4B26-8675-94DED121B6CD","generation":0}'
2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6EF2B7C6-F5B1-4B26-8675-94DED121B6CD, (syncValue: gmjUueoPyfvy9TZVAcFzQNJSUH8NYxwY)'
2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED12,1B6CD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6EF2B7C6-F5B1-4B26-8675-94DED121B6CD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
,2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2","generation":0}'
2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:807C7783-98F3-4BE0-A1E7-0746FC108957
[ThaliCore] Advertiser: session connected Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:807C7783-98F3-4BE0-A1E7-0746FC108957 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85616D03-A4E2-454E-A6D7-D1E511D69A3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85616D03-A4E2-454E-A6D7-D1E511D69A3B", generation: 0)
2017-07-26 15:27:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"85616D03-A4E2-454E-A6D7-D1E511D69A3B","generation":0}'
2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EF2B7C6-F5B1-4B26-8675-94DED121B6CD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,F2B7C6-F5B1-4B26-8675-94DED121B6CD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6EF2B7C6-F5B1-4B26-8675-94DED121B6CD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6EF2B7C6-F5B1-4B26-8675-94DED121B6CD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:807C7783-98F3-4BE0-A1E7-0746FC108957
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6EF2B7C6-F5B1-4B26-8675-94DED121B6CD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:807C7783-98F3-4BE0-A1E7-0746FC108957 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:807C7783-98F3-4BE0-A1E7-0746FC108957
,[ThaliCore] Session.startOutputStream(with:) peer:807C7783-98F3-4BE0-A1E7-0746FC108957
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [3, 5, 14]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:58A2E7BB-EEE5-4E37-AD4D-27D548A4E988
[ThaliCore] Advertiser: session connected Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:58A2E7BB-EEE5-4E37-AD4D-27D548A4E988 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EF2B7C6-F5B1-4B26-8675-94DED121B6CD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,F2B7C6-F5B1-4B26-8675-94DED121B6CD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-26 15:27:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gmjUueoPyfvy9TZVAcFzQNJSUH8NYxwY","error":"Peer is unavailable",,"portNumber":null}'
2017-07-26 15:27:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gmjUueoPyfvy9TZVAcFzQNJSUH8NYxwY', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-26 15:27:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-26 15:27:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2 (syncValue: 8wHt8YYdzJ86drhojwGU9zC,3c8dwVmml)'
2017-07-26 15:27:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4DF3451B-80F3-4259-BEC0-33FC5,EE7ACE2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:27:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6EF2B7C6-F5B1-4B26-8675-94DED121B6CD:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
2017-07-26 15:27:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1F9CF035-7C79-49E4-8780-3D74C1CE7552","generation":0}'
2017-07-26 15:27:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:46 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:27:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:58A2E7BB-EEE5-4E37-AD4D-27D548A4E988
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63587
2017-07-26 15:27:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8wHt8YYdzJ86drhojwGU9zC3c8dwVmml","error":null,"portN,umber":63587}'
,2017-07-26 15:27:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8wHt8YYdzJ86drhojwGU9zC3c8dwVmml', error: 'null', listeningPort: '63587''
,[ThaliCore] Session.session(_:peer:didChange:) peer:58A2E7BB-EEE5-4E37-AD4D-27D548A4E988 state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0) found active relay
,2017-07-26 15:27:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8RdaCq26bH09yEduDPfFFKXBBKAOI13r","error":null,"portNumber":63587}'
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:58A2E7BB-EEE5-4E37-AD4D-27D548,A4E988
[ThaliCore] Session.startOutputStream(with:) peer:58A2E7BB-EEE5-4E37-AD4D-27D548A4E988
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [3, 5, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0) found active relay
,2017-07-26 15:27:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hmibFfJ3fRMyB0ooyp4SAv661UoinGRm","error":null,"portNumber":63587}'
,ok 147 No error
,ok 148 Ports equal
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [3, 5, 14, 15, 16]
[ThaliCore] TCPClient: didConnectToHost, act,ive connections count: 0
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,# teardown
,2017-07-26 15:27:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 ,15:27:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore,] VirtualSocket.closeStreams() vsID:14
2017-07-26 15:27:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:), disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] Advertiser.stopAdvertising() peerID:6C4BE094-B690-45C8-8D11,-640C8096028F
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] AdvertiserRelay.didCloseVirtual,SocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [3, 5, 15, 16]
[ThaliCore] BrowserManager.disconnect peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2
[ThaliCore] BrowserRelay.c,loseRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63587
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[Thali,Core] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCo,re] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.dei,nit vsID:15 [3, 5, 16]
[ThaliCore] Session.disconnect() peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSoc,ket.deinit vsID:16 [3, 5]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] BrowserRelay.deinit
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:58A2E7BB-EEE5-4E37-AD4D-27D548A4E988 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:58A2E7BB-EEE5-4E37-AD4D-27D548A4E988
[ThaliCore] Advert,iserRelay.deinit
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:807C7783-98F3-4BE0-A1E7-0746FC108957 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
,# initial peer discovery
,2017-07-26 15:27:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:58A2E7BB-EEE5-4E37-AD4D-27D548A4E988
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
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-26 15:27:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:52 - DEBUG createNativeListener: 'listening 63592'
ok 149 Should throw
,# teardown
,2017-07-26 15:27:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:52 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'listening 63594'
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'listening 63597'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
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
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'listening 63601'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
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
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'listening 63606'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - close'
2017-07-26 15:27:54, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'listening 63610'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'listening 63614'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - close'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'listening 63618'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'listening 63622'
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
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
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
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
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
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
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
2017-07-26 15:27:57 - DEBUG createNativeListener: 'listening 63674'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-26 15:27:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'listening 63678'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:58 - DEBUG createNativeListener: 'listening 63681'
ok 196 port must be in range
,# teardown
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:58 - DEBUG createNativeListener: 'listening 63682'
ok 197 second start should return same port
,# teardown
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:59 - DEBUG createNativeListener: 'listening 63684'
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-26 15:27:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-26 15:27:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-26 15:27:59 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-26 15:27:59 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-26 15:27:59 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 63686
,ok 207 should be equal
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E937297E-E1AB-49DC-8BCB-38DF5390140B
,2017-07-26 15:28:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:28:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-26 15:28:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browse,r.init(serviceType:foundPeer:lostPeer:) peer:ADD585A6-B453-4207-A436-7E31657DF966
[ThaliCore] Browser.startListening
2017-07-26 15:28:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive",:true}'
,2017-07-26 15:28:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-26 15:28:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:85616D03-A4E2-454E-A6D7-D1E511D69A3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85616D03-A4E2-454E-A6D7-D1E511D69A3B", generation: 0)
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"1F9CF035-7C79-49E4-8780-3D74C1CE7552","generation":0}'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1F9CF035-7C79-49E4-8780-3D74C1CE7552 (syncValue: 0GOGEN01gBYWjVsDKSOxX53k1wP56Bli)'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[T,haliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifi,er":"85616D03-A4E2-454E-A6D7-D1E511D69A3B","generation":0}'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85E620C7-FC44-4A79-A50E-96D2E16AC7DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0)
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"85E620C7-FC44-4A79-A50E-96D2E16AC7DB","generation":0}'
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:34B62C2A-F0EA-47B5-919A-775C72B2336C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0)
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"34B62C2A-F0EA-47B5-919A-775C72B2336C","generation":0}'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E937297E-E1AB-49DC-8BCB-38DF5390140B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:85616D03-A4E2-454E-A6D7-D1E511D69A3B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "85616D03-A4E2-454E-A6D7-D1E511D69A3B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CD2D2900-859F-4060-B1A1-93BBF790160E
[ThaliCore] Advertiser: session connected Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CD2D2900-859F-4060-B1A1-93BBF790160E state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-26 15:28:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0GOGEN01gBYWjVsDKSOxX53k1wP56Bli","error":"Peer is unavailable",,"portNumber":null}'
2017-07-26 15:28:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0GOGEN01gBYWjVsDKSOxX53k1wP56Bli', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-26 15:28:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-26 15:28:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 85E620C7-FC44-4A79-A50E-96D2E16AC7DB (syncValue: DjbcNzhXU8KV9PQKaYGylur,BxAM27zfs)'
2017-07-26 15:28:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:85E620C7-FC44-4A79-A50E-96D2E,16AC7DB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:28:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:85E620C7-FC44-4A79-A50E-96D2E16AC7DB:0 state: notConnected -> connecting
,2017-07-26 15:28:10 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CD2D2900-859F-4060-B1A1-93BBF790160E
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:918FA0EB-D427-4759-8534-4F28BA1762FA
[ThaliCore] Advertiser: session connected Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:918FA0EB-D427-4759-8534-4F28BA1762FA state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD2D2900-859F-4060-B1A1-93BBF790160E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:85E620C7-FC44-4A79-A50E-96D2E16AC7DB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:85E620C7-FC44-4A79-A50E-96D2E16AC7DB:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63698
,2017-07-26 15:28:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DjbcNzhXU8KV9PQKaYGylurBxAM27zfs","error":null,"portNumber":63698}'
,2017-07-26 15:28:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DjbcNzhXU8KV9PQKaYGylurBxAM27zfs', error: 'null', listeningPort: '63698''
,ok 210 should be equal
,2017-07-26 15:28:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 34B62C2A-F0EA-47B5-919A-775C72B2336C (syncValue: 4liUlBmSc4g2Hzvwpkda16fYmlT2nmMX)'
,2017-07-26 15:28:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:34B62C2A-F0EA-47B5-919A-775C72B2336C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:34B62C2A-F0EA-47B5-919A-775C72B2336C:0 state: notConnected -> connecting
,2017-07-26 15:28:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:918FA0EB-D427-4759-8534-4F28BA1762FA
,[ThaliCore] Session.session(_:peer:didChange:) peer:918FA0EB-D427-4759-8534-4F28BA1762FA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:34B62C2A-F0EA-47B5-919A-775C72B2336C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:34B62C2A-F0EA-47B5-919A-775C72B2336C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63703
,2017-07-26 15:28:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4liUlBmSc4g2Hzvwpkda16fYmlT2nmMX","error":null,"portNumber":63703}'
,2017-07-26 15:28:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4liUlBmSc4g2Hzvwpkda16fYmlT2nmMX', error: 'null', listeningPort: '63703''
,ok 211 should be equal
,# teardown
,2017-07-26 15:28:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-26 15:29:16 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07,-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGG,ER result: passed - enqueue and run in order'
2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and en,queueAtTop'
2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously',
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-26 15:29:16 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Single coordinated request ios native, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737,D6C8/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/tim,ers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-26 15:29:16 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-26 15:29:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:36 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:350:16
$9@timers.js:120:1
''
,2017-07-26 15:31:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC,7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:45 - ERROR CoordinatedClient: 'reconnect_failed error: 'undefined', description: '%s', stack: '%s''
,2017-07-26 15:44:45 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-26 15:44:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4,FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B9CE5FD4-FF9C-4FC7-A2F2-224A5737D6C8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:45 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-07-26 15:44:45 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
