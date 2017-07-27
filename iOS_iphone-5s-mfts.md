#### Test 11335185130e646f_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/3B1F1F44-B11F-4046-9B57-A790A3E83993/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/3B1F1F44-B11F-4046-9B57-A790A3E83993/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51241"
,(lldb)     command script import "/tmp/3B1F1F44-B11F-4046-9B57-A790A3E83993/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,2017-07-27 09:38:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:38:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:38:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:38:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:38:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:38:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:38:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "45300CEF-8555-4C3E-87E3-FD90F89C8CC6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:45300CEF-8555-4C3E-87E3-FD90F89C8CC6
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DCD7213A-A44D-4914-83DD-27E18E1BDB7F
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A68BECEC-,B51C-4376-BE7D-73A23170C81D
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A01259CB-F706-4DFB-8A43-866BF670EC77", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:A01259CB-F706-4DFB-8A43-866BF670EC77
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01259CB-F706-4DFB-8A43-866BF670EC77:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01259CB-F706-4DFB-8A43-866BF670EC77", generation: 0)
AppContextTests.test_startAdv,ertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTes,ts finished
All tests finished
All tests finished
2017-07-27 09:38:12 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  13
,Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  1.695908010005951
,2017-07-27 09:38:12 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-07-27 09:38:12 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A01259CB-F706-4DFB-8A43-866BF670EC77:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A01259CB-F706-4DFB-8A43-866BF670EC77", generation: 0)
,2017-07-27 09:38:15 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-27 09:38:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-27 09:38:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-27 09:38:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-27 09:38:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-27 09:38:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-27 09:38:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-27 09:38:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-27 09:38:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-27 09:38:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-27 09:38:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-27 09:38:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-27 09:38:16 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-27 09:38:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-27 09:38:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-27 09:38:19 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-27 09:38:19 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-27 09:38:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:38:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:38:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:38:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:38:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:52 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-27 09:38:52 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-27 09:38:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-27 09:38:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-27 09:38:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-27 09:38:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-27 09:38:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-27 09:38:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-27 09:39:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-27 09:39:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,ok 29 firstPromise - in then
,ok 30 testing promises
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
,2017-07-27 09:39:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-27 09:39:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-27 09:39:12 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-27 09:39:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-27 09:39:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A0E5E127-BB65-462F-BC82-C2C87214BB2F
[ThaliCore] Browser.startListening
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-27 09:39:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:79EE851F-75D1-4175-839E-FB795C58873E
,[ThaliCore] Browser.startListening
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:39:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:39:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:17 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:17 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8223F44D-F410-4FC2-9118-28368E84EB25", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8223F44D-F410-4FC2-9118-28368E84EB25
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8223F44D-F410-4FC2-9118-28368E84EB25
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "98A78DE9-6AB5-4828-AD25-4CF0A6248282", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:98A78DE9-6AB5-4828-AD25-4CF0A6248282
2017-07-27 0,9:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "98A78DE9-6AB5-4828-AD25-4CF0A6248282", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:98A78DE9-6AB5-4828-AD25-4CF0A6248282
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:98A78DE9-6AB5-4828-AD25-4CF0A6248282
[ThaliCore] Advertiser.stopAdvertising() peerID:98A78DE9-6AB5-4828-AD25-4CF0A6248282
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:19 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "980AB9B2-4046-43E4-8FB8-434566707B01", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:980AB9B2-4046-43E4-8FB8-434566707B01
2017-07-27 0,9:39:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:14782D58-031C-42CD-917D-0AFC6FE457C0
[Thali,C,ore] Browser.startListening
,2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:39:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-27 09:39:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E915080D-D526-4FB8-80FE-E5B6C7288468:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E915080D-D526-4FB8-80FE-E5B6C7288468", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31037A71-18FB-4EDC-9425-AE037F466BC6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31037A71-18FB-4EDC-9425-AE037F466BC6", generation,: 0)
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:980AB9B2-4046-43E4-8FB8-434566707B01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "980AB9B2-4046-43E4-8FB8-434566707B01", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:980AB9B2-4046-43E4-8FB8-434566707B01
2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCha,nged registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "73A09F1E-56FB-45EF-99A3-14DCD6DE2211", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:73A09F1E-56FB-45EF-99A3-14DCD6DE2211
2017-07-27 0,9:39:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FB74A961-CFB9-44EC-A7B8-C64BFD36836A
[Thal,iCore] Browser.startListening
2017-07-27 09:39:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:39:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:39:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
2017-07-27 09:39:37 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"760B269A-1CC6-4302-B7BF-56CA6A0C4EC0","generation":0}'
2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 760B269A-1CC6-4302-B7BF-56CA6A0C4EC0, (syncValue: iqiKFdsqSyNVggOnQkn0R6njLMkl1Aia)'
,2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
,2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6","generation":0}'
,2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73A09F1E-56FB-45EF-99A3-14DCD6DE2211:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73A09F1E-56FB-45EF-99A3-14DCD6DE2211", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64170
,2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iqiKFdsqSyNVggOnQkn0R6njLMkl1Aia","error":null,"portNumber":64170}'
,2017-07-27 09:39:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iqiKFdsqSyNVggOnQkn0R6njLMkl1Aia', error: 'null', listeningPort: '64170''
,2017-07-27 09:39:40 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,2017-07-27 09:39:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 ,09:39:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-27 09:39:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:73A09F1E-56FB-45EF-99A3-1,4DCD6DE2211
,2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64170
[ThaliCore] Session.disconnect,() peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FE78BB24-6874-4581-AD57-0DC8832424B4
2017-07-27 0,9:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EC135E3A-28E7-492E-AE28-98B676DE705C
[ThaliCore] Browser.startListening
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:39:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
2017-07-27 09:39:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6","generation":0}'
2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6, (syncValue: RXz79OMbAA8NZKyv7t2wNI9giZsDSq8u)'
2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B32,21DD6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
2017-07-27 09:39:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9","generation":0}'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8", generation: 0)
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8","generation":0}'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6CA8AEF2-D177-43A2-9821-A81F72AC4C06
[ThaliCore] Advertiser: session connected Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6CA8AEF2-D177-43A2-9821-A81F72AC4C06 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6CA8AEF2-D177-43A2-9821-A81F72AC4C06
,[ThaliCore] Session.session(_:peer:didChange:) peer:6CA8AEF2-D177-43A2-9821-A81F72AC4C06 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6CA8AEF2-D177-43A2-9821-A81F72AC4C06
[ThaliCore] Session.startOutputStream(with:) peer:6CA8AEF2-D177-43A2-9821-A81F72AC4C06
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-27 09:39:49 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-27 09:39:49 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-27 09:39:49 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-27 09:39:49 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:4D7B1B88,-0FB5-4D2B-B0F3-0C19B3221DD6 error: max retries exceeded
2017-07-27 09:39:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RXz79OMbAA8NZKyv7t2wNI9giZsDSq8u","error":"Connection could not be established","portNumber":null}'
2017-0,7-27 09:39:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RXz79OMbAA8NZKyv7t2wNI9giZsDSq8u', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-27 09:39:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-27 09:39:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9 (syncValue: COv5LHY,9gAgaFOVLZuwIpCvkv1so8f6B)'
2017-07-27 09:39:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:64B3EA7D-E3EE,-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:39:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64179
,2017-07-27 09:39:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"COv5LHY9gAgaFOVLZuwIpCvkv1so8f6B","error":null,"portNumber":64179}'
,2017-07-27 09:39:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'COv5LHY9gAgaFOVLZuwIpCvkv1so8f6B', error: 'null', listeningPort: '64179''
,Connecting to the localhost:64179
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
,Connected to the localhost:64179
,2017-07-27 09:39:56 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-27 09:39:56 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-27 09:39:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 ,09:39:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-27 09:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FE78BB24-6874-4581-AD57-0,DC8832424B4
2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64179
,[ThaliCore] Session.disconnect() peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6CA8AEF2-D177-43A2-9821-A81F72AC4C06 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6CA8AEF2-D177-43A2-9821-A81F72AC4C06
,[ThaliCore] Session.deinit peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5284E402-404F-461B-A0AD-E6A5CA3CD24A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5284E402-404F-461B-A0AD-E6A5CA3CD24A
2017-07-27 0,9:39:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E
[ThaliCore] Browser.startListening
,2017-07-27 09:39:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:39:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-27 09:39:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:6CA8AEF2-D177-43A2-9821-A81F72AC4C06
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
2017-07-27 09:39:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9","generation":0}'
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9, (syncValue: TlSrRilMlKqBDLy2WFoqBpFx0ik534uF)'
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2,A7CD9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
2017-07-27 09:39:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A7A20DB4-FB47-4900-98BA-D663B3798342","generation":0}'
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:39:59 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5D887890-529C-4AA4-8B6E-27EF41303D,BD","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5284E402-404F-461B-A0AD-E6A5CA3CD24A", generation: 0)
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:64,B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,4B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:64,B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,4B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:64,B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,4B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:64,B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:64B3EA7D,-E3EE-4014-B73C-A9EA8C2A7CD9 error: max retries exceeded
2017-07-27 09:40:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TlSrRilMlKqBDLy2WFoqBpFx0ik534uF","error":"Connection could not be established","portNumber":null}'
2017-0,7-27 09:40:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TlSrRilMlKqBDLy2WFoqBpFx0ik534uF', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-27 09:40:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-27 09:40:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A7A20DB4-FB47-4900-98BA-D663B3798342 (syncValue: utW1SrZ,3fA9O3cTfJhEaPeqevC45oJ5W)'
2017-07-27 09:40:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A7A20DB4-FB47,-4900-98BA-D663B3798342:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:40:10 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t!'
,2017-07-27 09:40:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CB210357-920A-4640-B8A5-52F6C1925C45
[ThaliCore] Advertiser: session connected Peer(uuid: "5284E402-404F-461B-A0AD-E6A5CA3CD24A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CB210357-920A-4640-B8A5-52F6C1925C45 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CB210357-920A-4640-B8A5-52F6C1925C45
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CB210357-920A-4640-B8A5-52F6C1925C45 state: connecting -> connected
[ThaliCore] Session.session(_:peer:didChange:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0 state: connecting -> connected
[ThaliCore] ,Browser: session connected to Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64194
,2017-07-27 09:40:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"utW1SrZ3fA9O3cTfJhEaPeqevC45oJ5W","error":null,"portNumber":64194}'
,2017-07-27 09:40:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'utW1SrZ3fA9O3cTfJhEaPeqevC45oJ5W', error: 'null', listeningPort: '64194''
,Connecting to the localhost:64194
,Connecting to the localhost:64194
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
Connecting to the local,host:64194
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
,Connected to the localhost:64194
Connected to the localhost:64194
,Connected to the localhost:64194
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CB210357-920A-4640-B8A5-52F6C1925C45
[ThaliCore] Session.startOutputStream(with:) peer:CB210357-920A-4640-B8A5-52F6C1925C45
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CB210357-920A-4640-B8A5-52F6C1925C45
[ThaliCore] Session.startOutputStream(with:) peer:CB210357-920A-4640-B8A5-52F6C1925C45
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CB210357-920A-4640-B8A5-52F6C1925C45
[ThaliCore] Session.startOutputStream(with:) peer:CB210357-920A-4640-B8A5-52F6C1925C45
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [2, 3, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 3, 4, 5, 6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 3, 4, 5, 6, 7, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,ok 91 correct string length
,2017-07-27 09:40:13 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-27 09:40:13 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received (14235 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [2, 3, 4, 5, 7, 8]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError,:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received all data: ncgD7kv9fQhbU5qqH9MpcyTrymIzcmxVl6ySxYRgCmSjJIxFEQsxTsmgn735ZVSiwBZoS9huMu9o1VT5z38HIwyA6nWRIYJWI6eyHNLFNlUTZXsrB52uxpoqeZVWT3CAGEo70eBmtySQ2l4kyCk1EA6F2pMaeRDcE5d5Pl2YEURoqg4prt,jY33eAUnBGgbGkuH25aSXWh8MPuQE0yOraPPN7akuW6xPLZk3XIF7o2SM1B6LOn9RvVXCEk8V44Ob5EqNXO5npSsUxR2sovs96aq6ld933YhaaKit2Xu35OQS9sXe2vwmkce5zyjx3soTu6Xl7GDiW7D0sB9lMQpkDr8jqcXINcuQuulDdebBbRqovGhQyQnQo9X1HJINfLH0vRxRDpBcUTwbyqglqJUmpvl4KaymSYeAZPyouZBc8yiK7X7kYFy,AYEDFGKh6ykl9fYI6h3Nrlk8HdKjXi7TdJfwg9vN78GR6JKd7rUCxhWOP9qYivoJM36qSa0f3kWC1ahM6dYH7LhVe5wq0ytHWH1AP8P9lBhft38GpyKNbPIxP0zDRGyh2jxtVBwN47cyJ4fZWxptHhx7fZcHwybCaBtYIjW1lOrgn7SiU9rnzxjG4Jc2DpiohPXrVz7jFG4ZhLUYxSmaaYKa5XMfAq2mMb7XIvh4TNTEZbsWt7yw0J42yq6obtxK,by1beCjUBhBRFGajZXlAklg0pqISVG6GzPkOFHYmiXeFGX2w5RI46EmIBlguaLhdx1Yn1srDqWSzU3TU9cnIvESaoLCDDlxQEOlhbwL6G6eG6qWUMF5BLwVin2LNaiAEZOMYASZLcpXMWs4fV1S5xEjtBGoo1jvWyZHO5kFhWdKiLiVKm4ZHJetHa9QzzGDRGer10uwER5Og6HkO743d77D47dKRSd3XXK9cjN3pqqCgopJv2yn6JNbStWLCnsZE,Q1uA8Dp84pyOW5rxBB9w4H2jAHXjyzlAL9JXd0b1cCru3zvalrBhKobTqmIyUlr7Ucyt7wxKeidTbzpL4NmeDGKtasb3MReoDqTUYQxMjVFVjZUJDZp0EOs7QlunVCgX0P9VzED9dqki2h0hPSF9acgVMQbLhFkk0uQRwUmQnDGUxhAIXBnQf3Ata5FTijtiS3dibMwLz9DBXYXKEhA5I0eODl98KLCcPKbyArb8F66SXrQr4s1RfqOKVdOiVgQa,7gaSQgkZfDTZ64wI9PnZsj5Keo3Evr0FQzJmOFxGX77iRq8kpCtcMfDAMSwTWa5ieVS6ufRsT7exYZxF0wDfR8Pq4W3XXbzMlDzS8zpCWcXEF7kpLfqnGyJUuN4flW1blbYjHVX87aDxxZ8jjlxcJAb4qKbrOjqPpabbv1HznYXuFtuAPR2joEKFTIRdD3h9SPEVqbEiBrbh07PL15JVDHx8cYVYdOA5BOSJXcsPcaRwyWeqZwGdSBKrMYnVDFzH,GLNPxhZ80rAgehrv5oHSNOCn3x24HvjUWZ4wCnurfqzm1JVQzn3NCUMclnKXj4Exg4QAEGZu6YZHZTXqw2yVmlm87SbrGE6C4IAlb2cX4bEwMxXYEyar3NcQjfDh0QGhopRn1RfWLcNfJJiRjWbYJ90UmmA72oGFY5PGmQQVeiKpP56efvEruFT9rOb7Ih7635y6CTI9PS0GWqS5L2RJ1c254V7lmibgp3nRdfJ4BxJceBDpIDBonTSWDhG616es,aMFxwkrIFTePf4nO9696LpbiwhCoBYJfclyvbErANIDDEbIduouQ9L2q4ly98nXK7owNWbLvOr0m1RSmS4OzjbLcfiLJ7th60l8bQTMrStvxiEy9aJTe3SmeK9Px7BWH2lhzZszKJdfapE4Z4HupasdLn46NZ8pmyxxJFW4N9luaI4MKwDXetqE8TNkZ55EW1xTu21C7hXEmDCcWyWfQJGpRYub3vGuNn8PNEKOmqzLek9xrQaGyOVM4zQEgFGCc,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,mJ0JjtG8CU5dm8XmDrAYooSRKY1U2UEJZGoBjQemfBKO7HxMKFDiMqGjmapCZeYwwooGYEP2Ssq5vXq28tTkGAPtSGvFxHKJqDIvqrpHQHLQgrFULEYHo2xMIRqYjhnhmvPlKTaXKS75bxfbsblxm7D4aaOVws45j0jtFQId0HgLP2OeP1LC3u7dvozGqktc7xtv3SLpJmuZlnSqcFqgpkyDtuMzErbuwh1eul0a97zDzFEjmvaReN73et2ro5Nk,ZGclypo1OXzk0Z8lT0ZdRBmSGHQsbO12cEC9m19kqZ1nHmH62o79GQZlkXev4h6SfelR64wNf4KLdvf6cbp9WOH2gExZ8Q9XieswvIJ4EYYd2petp8U1sxopYgbdacYwDZO4Wc3SokyIHH9D4nKPwIlPwns9ADZkuo0vQYeoAPWyQ1GB8cbXq1cueeKJCYZvtoGK3V0uCA8sdzL5H9SR357QCiCdhEzyPL8NQ5hgGw1mXXi2k0VmL6h7qWoUldJH,uDwN85TmNatyEhVpMvz7KnJItP6d8LNC4yJ4RZQdhTlwZE62AQVC5vhNvoxhr8YoWacMqEog4sAk6oszbE1DiqznlAfYd47vp9wdPJzMf3eT04rzl2IQZkZSN9iOK5Us53R4Sx7w0vAjpSr55bC7XFg2AFy14ZAMDHln4f5FMY8woHeSiXCY8gxlwKD6si6hmSwVPbclbeZTmFqMn9XyuzkZaLtjX05fSiTMeT42Mz263rOFKpMPWHgqtY3SlJfJ,dZESdRfJZfh0tr3bTItLvFAUy4CwFF57TIP5QI1U9yti4wZX5n8dN40C8O4fUpWRHRh7tFVBmrOq94F4zkWvNHbxUw6ZuknRvtR7aOeXspOpMaGS7Tng5GTZZZr5JHwEHSMPjY8yKjptAOBaVCDxJawEN2NbVTVbDmzB9cIB497VYaYmM4q1wnxbAfy4fWfJNoGQJeArW9CT9neJpsSWBfNEgfQamEh8QOnTbhUmDp0q6exEMkPLQq1CqLCRX4Yw,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
wBjoebyfy,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'
2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:5 [2, 3, 4, 7, 8]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [2, 3, 7, 8]
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [2, 3, 7]
,ok 96 got the same data back
,# teardown
,2017-07-27 09:40:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:40:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CB210357-920A-4640-B8A5-52F6C1925C45 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5284E402-404F-461B-A0AD-E6A5CA3CD24A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:CB210357-920A-4640-B8A5-52F6C1925C45
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:5284E402-404F-461B-A0AD-E6A5CA3CD24A
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:A7A20DB4-FB47-4900-98BA-D663B3798342
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64194
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"utW1SrZ3fA9O3cTfJhEaPeqevC45oJ5W","error":"Session disconnected","portNumber":null}'
,# Can shift data securely
[ThaliCore] Session.deinit peer:CB210357-920A-4640-B8A5-52F6C1925C45
[ThaliCore] Session.deinit peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4F597521-BA0A-4144-A2E4-1D226FF5B49F
,2017-07-27 09:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:40:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:40:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAd,vertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9FB87A3C-114D-4621-9A00-25A3A52DF757
[ThaliCore] Browser.startListening
2017-07-27 09:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":true,"advertisingActive":true}'
,2017-07-27 09:40:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-27 09:40:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
2017-07-27 09:40:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5D887890-529C-4AA4-8B6E-27EF41303DBD","generation":0}'
2017-07-27 09:40:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5D887890-529C-4AA4-8B6E-27EF41303DBD, (syncValue: kaALvnSAxJgaDsyD9Xl2QFH1l09aEoIe)'
2017-07-27 09:40:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF413,03DBD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:90F04B47-253B-44D4-BB34-B5C287986AB0:0
2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E27FBB5D-EE77-449F-841C-C5B2D7938662","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90F04B47-253B-44D4-BB34-B5C287986AB0", generation: 0)
2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already r,unning test!'
2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"90F04B47-253B-44D4-BB34-B5C287986AB0","generation":0}'
2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running t,est!'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5D,887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5D,887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5D,887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5D,887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5D887890,-529C-4AA4-8B6E-27EF41303DBD error: max retries exceeded
2017-07-27 09:40:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kaALvnSAxJgaDsyD9Xl2QFH1l09aEoIe","error":"Connection could not be established","portNumber":null}'
2017-0,7-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kaALvnSAxJgaDsyD9Xl2QFH1l09aEoIe', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-27 09:40:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E27FBB5D-EE77-449F-841C-C5B2D7938662 (syncValue: LZZ7Skd,Jmhw7TpI4XoSQ87QpSeEcnTd1)'
2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E27FBB5D-EE77,-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64215
2017-07-27 09:40:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LZZ7SkdJmhw7TpI4XoSQ87QpSeEcnTd1",,"error":null,"portNumber":64215}'
2017-07-27 09:40:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LZZ7SkdJmhw7TpI4XoSQ87QpSeEcnTd1', error: 'null', listeningPort: '64215''
,Connecting to the localhost:64215
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [2, 3, 7, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:64215
,2017-07-27 09:40:31 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-27 09:40:31 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
,[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# teardown
,2017-07-27 09:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 ,09:40:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-27 09:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4F597521-BA0A-4144-A2E4-1,D226FF5B49F
2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:E27FBB5D-EE77-449F-841C-C5B2D7938662
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64215
[ThaliCore] Session.disconnect() p,eer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdve,rtisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D
,2017-07-27 09:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B1E49570-D25C-4E1C-B54E-3EDDB2FD7150
[ThaliCore] Browser.startList,ening
2017-07-27 09:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
,2017-07-27 09:40:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E27FBB5D-EE77-449F-841C-C5B2D7938662","generation":0}'
,2017-07-27 09:40:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E27FBB5D-EE77-449F-841C-C5B2D7938662 (syncValue: KbY2Tb9C9zBmoBRJgVRR9wRdlSvmJv1p)'
,2017-07-27 09:40:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D028B2EF-4493-4F02-B3B2-E9956CFE8164","generation":0}'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61237622-BEF2-4351-A24C-AE880E588319:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation: 0)
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"61237622-BEF2-4351-A24C-AE880E588319","generation":0}'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E2,7FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E2,7FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E2,7FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:40:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KbY2Tb9C9zBmoBRJgVRR9wRdlSvmJv1p","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:40:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KbY2Tb9C9zBmoBRJgVRR9wRdlSvmJv1p', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:40:47 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:40:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D028B2EF-4493-4F02-B3B2-E9956CFE8164 (syncValue: kgumVHliZ7ja5Hj7OTYqxEN,jY85CdhpV)'
2017-07-27 09:40:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D028B2EF-4493-4F02-B3B2-E9956,CFE8164:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:40:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64229
2017-07-27 09:40:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kgumVHliZ7ja5Hj7OTYqxENjY85CdhpV",,"error":null,"portNumber":64229}'
,2017-07-27 09:40:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kgumVHliZ7ja5Hj7OTYqxENjY85CdhpV', error: 'null', listeningPort: '64229''
,Connecting to the localhost:64229
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
,Connected to the localhost:64229
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [2, 3, 7, 9, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:40:49 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-27 09:40:49 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:10 [2, 3, 7, 9]
,ok 102 got the same data back
,# teardown
,2017-07-27 09:40:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:40:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:40:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64229
[ThaliCore] Session.disconnect() peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:22F9CF2B-34E5-4A74-8A7B-70E76D7B5002
[ThaliCore] Browser.startListening
2017-07-27 09:40:51 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:40:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:40:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:,errorHandler:) Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8450063C-E352-4DE2-8028-790BEAC33A89
2017-07-27 09:40:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpda,teNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:40:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"net,workType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61237622-BEF2-4351-A24C-AE880E588319:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation: 0)
2017-07-27 09:40:51 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"61237622-BEF2-4351-A24C-AE880E588319","generation":0}]'
2017-07-27 09:40:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"61237622-BEF2-4351-A24C-AE880E588319","generation":0}'
2017-07-27 09:40:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
,2017-07-27 09:40:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D028B2EF-4493-4F02-B3B2-E9956CFE8164","generation":0}]'
,2017-07-27 09:40:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D028B2EF-4493-4F02-B3B2-E9956CFE8164","generation":0}'
,2017-07-27 09:40:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8450063C-E352-4DE2-8028-790BEAC33A89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
2017-07-27 09:40:52 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"043B6E7B-5BF1-4D4E-A18A-4039818E34E6","generation":0}]'
2017-07-27 09:40:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"043B6E7B-5BF1-4D4E-A18A-4039818E34E6","generation":0}'
2017-07-27 09:40:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4EC8ABF-9651-4E51-A4EB-1008683F3A0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4EC8ABF-9651-4E51-A4EB-1008683F3A0E", generation: 0)
2017-07-27 09:40:53 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F4EC8ABF-9651-4E51-A4EB-1008683F3A0E","generation":0}]'
2017-07-27 09:40:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F4EC8ABF-9651-4E51-A4EB-1008683F3A0E","generation":0}'
2017-07-27 09:40:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
2017-07-27 09:40:55 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"D028B2EF-4493-4F02-B3B2-E9956CFE8164","generation":0}]'
2017-07-27 09:40:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"D028B2EF-4493-4F02-B3B2-E9956CFE8164","generation":0}'
2017-07-27 09:40:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8450063C-E352-4DE2-8028-790BEAC33A89
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-27 09:40:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F97FD7C9-1BFF-45AE-AAE1-C52668917773
[ThaliCore] Browser.startListening
ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpd,ateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8A9B4818-EF9D-4990-8407-8525C08D23D1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8A9B4818-EF9D-4990-8407-8525C08D23D1
ok 107 discoveryActive should be false
ok 108 adv,ertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8A9B4818-EF9D-4990-8407-8525C08D23D1
ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-27 09:40:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-27 09:40:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-27 09:41:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-27 09:41:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-27 09:41:00 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-27 09:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-27 09:41:02 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-27 09:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-27 09:41:02 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-27 09:41:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-27 09:41:03 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-27 09:41:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:ac9918c7-e7df-43bc-a144-6f1d37550aa5 error: startListeningNotActive
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9bNe0RtdYEap0uBDwLSW8aowXcpmlEoH","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:06 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:982D1F59-F4FF-430A-87E7-A95811A91F92
[ThaliCore] Browser.startListening
2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:41:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mpl1I2S9a4gviSWNeZq3dPQ3mqxSvYdC","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"043B6E7B-5BF1-4D4E-A18A-4039818E34E6","generation":0}]'
2017-07-27 09:41:07 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"043B6E7B-5BF1-4D4E-A18A-4039818E34E6","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61237622-BEF2-4351-A24C-AE880E5883,19:0
2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation:, 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"61237622-BEF2-4351-A24C-AE880E588319","generation":0}]'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"61237622-BEF2-4351-A24C-AE880E588319","generation":0}'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-27 09:41:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:08 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:15269BEE-2B07-4301-BE19-76E6298E7036
[ThaliCore] Browser.startListening
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-27 09:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:09 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:10 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:ad5a8c2e-ce3c-468c-acac-a3984bbc71b8
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68
2017-07-27 0,9:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4B01804B-5851-4C3A-B1D3-915D446925C1
[Tha,l,iCore] Browser.startListening
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"043B6E7B-5BF1-4D4E-A18A-4039818E34E6","generation":0}'
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 043B6E7B-5BF1-4D4E-A18A-4039818E34E6 (syncValue: 0V9OwOjnEmYAusW6SeePXOuS6zM2A0ZD)'
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E4673876-CD79-4B66-A02B-FE40C77AED43:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E4673876-CD79-4B66-A02B-FE40C77AED43", generation: 0)
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E4673876-CD79-4B66-A02B-FE40C77AED43","generation":0}'
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
2017-07-27 09:41:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8205ADF4-3323-4842-8B88-4588EAF9E8A1","generation":0}'
2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:41:12 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CEBD3BAD-7736-47D6-AA03-A37F3F1EE6F2
[ThaliCore] Advertiser: session connected Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CEBD3BAD-7736-47D6-AA03-A37F3F1EE6F2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:04,3B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,43B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CEBD3BAD-7736-47D6-AA03-A37F3F1EE6F2
,[ThaliCore] Session.session(_:peer:didChange:) peer:CEBD3BAD-7736-47D6-AA03-A37F3F1EE6F2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CEBD3BAD-7736-47D6-AA03-A37F3F1EE6F2
,[ThaliCore] Session.startOutputStream(with:) peer:CEBD3BAD-7736-47D6-AA03-A37F3F1EE6F2
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [2, 3, 7, 9, 11]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:41:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0V9OwOjnEmYAusW6SeePXOuS6zM2A0ZD","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0V9OwOjnEmYAusW6SeePXOuS6zM2A0ZD', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:41:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:41:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E4673876-CD79-4B66-A02B-FE40C77AED43 (syncValue: 4c6EWU78wnsxmV1ha1dyxRs,CGrIFpKtT)'
2017-07-27 09:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E4673876-CD79-4B66-A02B-FE40C77AED43", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E4673876-CD79-4B66-A02B-FE40C77AED43", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E4673876-CD79-4B66-A02B-FE40C77AED43:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:41:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E4673876-CD79-4B66-A02B-FE40C77AED43:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:03646242-A0E1-44F0-91FC-87940E6C4419
[ThaliCore] Advertiser: session connected Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:03646242-A0E1-44F0-91FC-87940E6C4419 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E4673876-CD79-4B66-A02B-FE40C77AED43:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E4673876-CD79-4B66-A02B-FE40C77AED43:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E4673876-CD79-4B66-A02B-FE40C77AED43", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64241
,2017-07-27 09:41:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4c6EWU78wnsxmV1ha1dyxRsCGrIFpKtT","error":null,"portNumber":64241}'
,2017-07-27 09:41:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4c6EWU78wnsxmV1ha1dyxRsCGrIFpKtT', error: 'null', listeningPort: '64241''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E4673876-CD79-4B66-A02B-FE40C77AED43:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E4673876-CD79-4B66-A02B-FE40C77AED43", generation: 0) found active relay
,2017-07-27 09:41:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pXpIiB473EOj3MkpfnZvX50ajShHHSbi","error":null,"portNumber":64241}'
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E4673876-CD79-4B66-A02B-FE40C7,7AED43:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [2, 3, 7, 9, 11, 12]
ok 144 No error
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E4673876-CD79-4B66-A02B-FE40C77AED43", generation: 0) found active relay
,2017-07-27 09:41:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NcrbL6qv7he9mf00gVehOwbm8KJLLGcd","error":null,"portNumber":64241}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:03646242-A0E1-44F0-91FC-87940E6C4419
[ThaliCore] Advertiser: session connected Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:03646242-A0E1-44F0-91FC-87940E6C4419 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:03646242-A0E1-44F0-91FC-87940E6C4419
,[ThaliCore] Session.session(_:peer:didChange:) peer:03646242-A0E1-44F0-91FC-87940E6C4419 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:03646242-A0E1-44F0-91FC-87940E6C4419
,[ThaliCore] Session.startOutputStream(with:) peer:03646242-A0E1-44F0-91FC-87940E6C4419
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [2, 3, 7, 9, 11, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-27 09:41:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68
2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09,:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:E4673876-CD79-4B66-A02B-FE40C77AED43
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64241
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] Session.session(_:peer:didChange:) peer:03646242-A0E1-44F0-91FC-87940E6C4419 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket exited RunLoop vsID:12,
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket cl,osed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] Session.disconnect() peer:E4673876-CD79-4B66-A02B-FE40C77AED43:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] TCPClient.socketDidDisconnect(,_:withError:) client disconnected
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" ,UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:12 [2, 3, 7, 9, 11, 13]
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:03646242-A0E1-44F0-91FC-87940E6C4419
[ThaliCore], VirtualSocket.deinit vsID:13 [2, 3, 7, 9, 11]
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [2, 3, 7, 9]
,[ThaliCore] Session.session(_:peer:didChange:) peer:CEBD3BAD-7736-47D6-AA03-A37F3F1EE6F2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,[ThaliCore] Session.deinit peer:E4673876-CD79-4B66-A02B-FE40C77AED43:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:03646242-A0E1-44F0-91FC-87940E6C4419
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-27 09:41:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-27 09:41:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:41:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-27 09:41:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-27 09:41:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-27 09:41:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-27 09:41:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'listening 64245'
,ok 149 Should throw
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:03646242-A0E1-44F0-91FC-87940E6C4419 state: connecting -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,2017-07-27 09:41:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'listening 64247'
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'listening 64250'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'listening 64254'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-27 09:41:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'listening 64259'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'listening 64263'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'listening 64267'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'listening 64271'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'listening 64275'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-27 09:41:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'listening 64327'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'listening 64331'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:35 - DEBUG createNativeListener: 'listening 64334'
ok 196 port must be in range
,# teardown
,2017-07-27 09:41:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'listening 64335'
,ok 197 second start should return same port
,# teardown
,2017-07-27 09:41:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'listening 64337'
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-27 09:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-27 09:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-27 09:41:36 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-27 09:41:36 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-27 09:41:36 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 64339
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6EA0C969-35BA-462D-8165-A0BABFC74371
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BC9BDDF8-215E-43EF-9BEA-8B22BA7ACE4C
,[ThaliCore] Browser.startListening
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-27 09:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F2620B9A-00C1-4B34-8AA8-6CE552013511","generation":0}'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F2620B9A-00C1-4B34-8AA8-6CE552013511 (syncValue: ja5hYPyu78SmK44c0SWxar7cUZowhQNE)'
2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8205ADF4-3323-4842-8B88-4588EAF9E8A1","generation":0}'
2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D","generation":0}'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64346
2017-07-27 09:41:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ja5hYPyu78SmK44c0SWxar7cUZowhQNE","error":null,"portN,umber":64346}'
,2017-07-27 09:41:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ja5hYPyu78SmK44c0SWxar7cUZowhQNE', error: 'null', listeningPort: '64346''
,ok 210 should be equal
,2017-07-27 09:41:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D (syncValue: c0iPT5BQd2D7SoNM8Om0gWw6lZHAmZw9)'
,2017-07-27 09:41:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64350
,2017-07-27 09:41:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"c0iPT5BQd2D7SoNM8Om0gWw6lZHAmZw9","error":null,"portNumber":64350}'
,2017-07-27 09:41:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'c0iPT5BQd2D7SoNM8Om0gWw6lZHAmZw9', error: 'null', listeningPort: '64350''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:878DACE9-3741-43AD-9FBE-AB693BD154B7
[ThaliCore] Advertiser: session connected Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:878DACE9-3741-43AD-9FBE-AB693BD154B7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:878DACE9-3741-43AD-9FBE-AB693BD154B7
,[ThaliCore] Session.session(_:peer:didChange:) peer:878DACE9-3741-43AD-9FBE-AB693BD154B7 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:043B36AE-A7EF-45C0-AEC3-D1596533F824
[ThaliCore] Advertiser: session connected Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:043B36AE-A7EF-45C0-AEC3-D1596533F824 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:043B36AE-A7EF-45C0-AEC3-D1596533F824
,[ThaliCore] Session.session(_:peer:didChange:) peer:043B36AE-A7EF-45C0-AEC3-D1596533F824 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:42:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6EA0C969-35BA-462D-8165-A0BABFC74371
,2017-07-27 09:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:F2620B9A-00C1-4B34-8AA8-6CE552013511
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64346
,[ThaliCore] Session.disconnect() peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64350
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:043B36AE-A7EF-45C0-AEC3-D1596533F824 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:043B36AE-A7EF-45C0-AEC3-D1596533F824
,[ThaliCore] Session.deinit peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:42:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:878DACE9-3741-43AD-9FBE-AB693BD154B7 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
,# Multiple local http requests
,[ThaliCore] Session.deinit peer:043B36AE-A7EF-45C0-AEC3-D1596533F824
,listening on 64352
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F26BEBDA-8461-458A-80B4-5C81D72A6F32
2017-07-27 0,9:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:42:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FBE91978-6593-4C2C-80BD-6B5270525409
[ThaliCore] Browser.startListening
2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-27 09:42:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
2017-07-27 09:42:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F2620B9A-00C1-4B34-8AA8-6CE552013511","generation":0}'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F2620B9A-00C1-4B34-8AA8-6CE552013511, (syncValue: IdcHq3jRIQNUIMKKBfXMSVFCiwo3KIEV)'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE5520,13511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
2017-07-27 09:42:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D","generation":0}'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
2017-07-27 09:42:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}'
2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:42:03 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
2017-07-27 09:42:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}'
2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:42:03 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F2,620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F2,620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F2,620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:42:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IdcHq3jRIQNUIMKKBfXMSVFCiwo3KIEV","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:42:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IdcHq3jRIQNUIMKKBfXMSVFCiwo3KIEV', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:42:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-27 09:42:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E0ECECFD-99D4-4837-84C7-C4E68676530E (syncValue: f0BzaHjm1XXecly9m5k6HYL6xgm0e2FV)'
,2017-07-27 09:42:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:42:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64368
,2017-07-27 09:42:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"f0BzaHjm1XXecly9m5k6HYL6xgm0e2FV","error":null,"portNumber":64368}'
2017-07-27 09:42:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'f,0BzaHjm1XXecly9m5k6HYL6xgm0e2FV', error: 'null', listeningPort: '64368''
,ok 217 should be equal
,ok 218 should be equal
ok 219 should be equal
2017-07-27 09:42:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E7703811-CCCA-4D64-BE3F-2CE0B9423AE0 (syncValue: AUGMlRlbnIOL0FZx065qXE5rslxI6tSH)'
2017-07-27 09:42:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64374
2017-07-27 09:42:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AUGMlRlbnIOL0FZx065qXE5rslxI6tSH",,"error":null,"portNumber":64374}'
2017-07-27 09:42:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AUGMlRlbnIOL0FZx065qXE5rslxI6tSH', error: 'null', listeningPort: '64374''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B262399-1BC1-4506-9E08-61EB06510EB1
[ThaliCore] Advertiser: session connected Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2B262399-1BC1-4506-9E08-61EB06510EB1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2B262399-1BC1-4506-9E08-61EB06510EB1
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B262399-1BC1-4506-9E08-61EB06510EB1 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD
[ThaliCore] Advertiser: session connected Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD
,[ThaliCore] Session.session(_:peer:didChange:) peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:42:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F26BEBDA-8461-458A-80B4-5C81D72A6F32
2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:E0ECECFD-99D4-4837-84C7-C4E68676530E,
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64368
[ThaliCore] Session.disconnect() peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64374
,[ThaliCore] Session.disconnect() peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B262399-1BC1-4506-9E08-61EB06510EB1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
,[ThaliCore] Session.deinit peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD
[ThaliCore] Session.deinit peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserRelay.deinit
2017-07-27 09:42:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:29 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:42:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-27 09:42:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 227 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:30 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'listening 64378'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FBBBB1FB-9122-4639-8967-17D835660E82
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
2017-07-27 09:42:30 - INFO th,aliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
,# teardown
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}]'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}]'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 230 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'listening 64379'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D3777C0E-B16E-4644-891E-354111A79D1B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D3777C0E-B16E-4644-891E-354111A79D1B
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D3777C0E-B16E-4644-891E-354111A79D1B", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:D3777C0E-B16E-4644-891E-354111A79D1B
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D3777C0E-B16E-4644-891E-354111A79D1B
,[ThaliCore] Advertiser.stopAdvertising() peerID:D3777C0E-B16E-4644-891E-354111A79D1B
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 233 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'listening 64382'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 236 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 237 network status should have certain non-empty properties
,# teardown
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-27 09:42:31 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 239 specific error expected
,# teardown
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'listening 64383'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:823420E8-97F4-46A1-9A49-7561FB77DCF5
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "01F2FD00-EF99-4FCF-A912-1A5FE23F4CF7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:01F2FD00-EF99-4FCF-A912-1A5FE23F4CF7
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 241 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:01F2FD00-EF99-4FCF-A912-1A5FE23F4CF7
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'listening 64386'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A12D78BC-8CBF-4AE8-8BBA-241B19B5F722
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C0BB9146-4CAC-493C-B3A5-610ABC17D2D9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C0BB9146-4CAC-493C-B3A5-610ABC17D2D9
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C0BB9146-4CAC-493C-B3A5-610ABC17D2D9
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'listening 64388'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:29BB8D25-45CB-4828-A671-A92CA40D534F
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A53283D3-27A6-4888-B308-7731E2E4DB54", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A53283D3-27A6-4888-B308-7731E2E4DB54
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A53283D3-27A6-4,888-B308-7731E2E4DB54
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 245 is stopped after calling stop
,ok 246 connection should fail after stopping
,# teardown
,ok 247 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-27 09:42:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 248 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 249 error description matches
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-27 09:42:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 251 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:34 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 252 error description matches
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 254 IMPLEMENT ME!!!!!!
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:35 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:35 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-27 09:42:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 256 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-27 09:42:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-27 09:42:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-27 09:42:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 260 NOT IMPLEMENTED # SKIP
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-27 09:42:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-27 09:42:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-27 09:42:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:38 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-27 09:42:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'listening 64391'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ED9F58C5-F1CC-442A-972D-4CD514AD7831
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 266 discoveryActive matches
,ok 267 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,2017-07-27 09:42:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'listening 64392'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "639404CC-7285-4557-B339-D68AF1601599", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:639404CC-7285-4557-B339-D68AF1601599
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:639404CC-7285-4557-B339-D68AF1601599
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'listening 64394'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 274 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'listening 64395'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5FE6EFEE-2AEC-4EDA-9AEF-4CF0A9E10F02
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1AD4E328-1AC8-42F2-840E-E312222887D5
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:51E3490C-3571-426B-910E-CC3E35165F7B:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "51E3490C-3571-426B-910E-CC3E35165F7B", generation: 0)
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-48,37-84C7-C4E68676530E","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWr,apper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}]'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}'
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}]'
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"pe,erAvailable":true,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}]'
2017-07-27 09:42:40 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 275 portNumber equal null
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:1AD4E328-1AC8-42F2-840E-E312222887D5
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:40 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-27 09:42:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 277 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-27 09:42:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-27 09:42:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:42 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'listening 64397'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:59628830-82CA-4182-B076-3090507B3592
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:97AC027D-E887-4A31-AA7D-B254708661C6
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:51E3490C-3571-426B-910E-CC3E35165F7B:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "51E3490C-3571-426B-910E-CC3E35165F7B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","generation":0}]'
2017-07-27 09:42:43 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","generation":0}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}]'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}'
2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}]'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}]'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6ECF630A-A1AB-4826-8FC0-E527CADCE577 (syncValue: y9pCvdAipyIME7xPuXcPuc66jZabEjLC)'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64401
2017-07-27 09:42:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"y9pCvdAipyIME7xPuXcPuc66jZabEjLC",,"error":null,"portNumber":64401}'
2017-07-27 09:42:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'y9pCvdAipyIME7xPuXcPuc66jZabEjLC', error: 'null', listeningPort: '64401''
,2017-07-27 09:42:45 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [2, 3, 7, 9, 14]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:42:47 - DEBUG testUtils: 'Got response data'
,2017-07-27 09:42:47 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
,ok 282 must be started
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:51E3490C-3571-426B-910E-CC3E35165F7B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "51E3490C-3571-426B-910E-CC3E35165F7B", generation: 0)
,2017-07-27 09:42:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}]'
2017-07-27 09:42:48 - DEBUG thaliMobileNative,Wrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
,2017-07-27 09:42:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-27 09:42:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:42:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}]'
2017-07-27 09:42:48 - DEBUG thaliMobileNative,Wrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}'
,2017-07-27 09:42:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-27 09:42:48 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:97AC027D-E887-4A31-AA7D-B254708661C6
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64401
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] Session.disconnect() peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [2, 3, 7, 9]
,[ThaliCore] Session.deinit peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 284 FIX ME, PLEASE!!!
,# teardown
,ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:55 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-27 09:42:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:55 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-27 09:42:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 288 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 289 specific error should be returned
,# teardown
,2017-07-27 09:42:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:42:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:42:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:42:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 290 error should be null
,ok 291 error should be null
,# setup
,ok 292 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 293 specific error should be returned
,# teardown
,ok 294 error should be null
ok 295 error should be null
,# setup
,ok 296 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'listening 64403'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 297 error should be null
ok 298 error shoul,d be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 301 error should be null
ok 302 error should be null
,# setup
,ok 303 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'listening 64404'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:86E35098-B504-4BD3-BD1D-F8A07231C1F1
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 304 error should be null
,ok 305 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
,ok 307 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:57 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateU,pdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advert,isingActive":false}'
2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 308 error should be null
,ok 309 error should be null
,# setup
,ok 310 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'listening 64405'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D12B0782-0BE0-4C86-9309-E17830953AF4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D12B0782-0BE0-4C86-9309-E17830953AF4
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 311 error should be null
ok 312 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D12B0782-0BE0-4C86-9309-E17830953AF4", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:D12B0782-0BE0-4C86-9309-E17830953AF4
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D12B0782-0BE0-4C86-9309-E17830953AF4
,[ThaliCore] Advertiser.stopAdvertising() peerID:D12B0782-0BE0-4C86-9309-E17830953AF4
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
,ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'listening 64408'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 318 error should be null
,ok 319 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 error should be null
,ok 323 error should be null
,# setup
,ok 324 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-27 09:42:58 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 325 This should not cause wifi to fail
ok 326 native router should be bad
,# teardown
,ok 327 error should be null
,ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-27 09:42:59 - DEBUG thaliMobileNativeWrapper: 'listening 64409'
,ok 330 first call should succeed
,ok 331 first call should succeed
,ok 332 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 333 error should be null
,ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-27 09:42:59 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 336 error should be null
,ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-27 09:42:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 339 error should be null
,ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-27 09:42:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a5c56ad9-cbe9-49da-85d5-cb431d4c762c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 342 should be called once
,ok 343 should not have been called more than once
,# teardown
,2017-07-27 09:42:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a5c56ad9-cbe9-49da-85d5-cb431d4c762c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 344 error should be null
,ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# can get the network status
,ok 347 network status should have certain non-empty properties
,# teardown
,ok 348 error should be null
ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 351 we have not added peer to the cache yet
2017-07-27 09:43:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6fbdb796-d505-47d2-b798-7fcd8b62eaab","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 352 peer should be available
ok 353 cache contains native peer
2017-07-27 09:43:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6fbdb796-d505-47d2-b798-7fcd8b62eaab","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 354 peer should be unavailable
ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
,ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"70e7e119-de3f-4c5c-a115-03c585dc3ce8","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 360 peer should be available
ok 361 cache contains wifi peer
2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"70e7e119-de3f-4c5c-a115-03c585dc3ce8","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 362 peer should be unavailable
,ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c1c99a09-20d5-428a-91a4-e19e8f8930b7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 367 first peer is a,vailable
2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"48a12c05-3826-44c0-a07e-6249523bf55a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 368 second, peer is available
ok 369 first and second peers are different
,# teardown
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c1c99a09-20d5-428a-91a4-e19e8f8930b7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"48a12c05-3826-44c0-a07e-6249523bf55a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
,ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f38ea97c-a01d-4240-9707-f873e205fec9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 374 peer is available
,# teardown
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f38ea97c-a01d-4240-9707-f873e205fec9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 375 error should be null
,ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-27 09:43:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 378 error should be null
,ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-27 09:43:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 381 error should be null
,ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"540b5393-96fa-4cd5-a245-b341b04cbbec","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 384 peer should be ,available
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"540b5393-96fa-4cd5-a245-b341b04cbbec","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 385 peer should be ,available
ok 386 should store correct generation
,# teardown
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"540b5393-96fa-4cd5-a245-b341b04cbbec","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
,ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-27 09:43:02 - DEBUG thaliMobileNativeWrapper: 'listening 64410'
2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"da01e8c7-7aa9-4379-b61c-aa4683527d5a","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 390 discovered correct peer
ok 391 got correct generation
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"da01e8c7-7aa9-4379-b61c-aa4683527d5a","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,# teardown
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"da01e8c7-7aa9-4379-b61c-aa4683527d5a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 394 error should be null
,ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'listening 64411'
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ecd49eab-f67e-4233-9ea0-91790ee2a9f2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 397 discovered available peer
,ok 398 peer is available
,# teardown
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ecd49eab-f67e-4233-9ea0-91790ee2a9f2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 399 error should be null
,ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"87bcc08d-6e1e-4cd7-ba0c-e6840b0040eb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 402 peer should be available
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"87bcc08d-6e1e-4cd7-ba0c-e6840b0040eb","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 403 peer should be unavailable
,ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'listening 64412'
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6ab3ed20-5272-40ac-ad00-a27cb46cf20f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 first peer is expected to be available
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97171fd7-5a90-48e0-9f30-6ab3c966b959","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 409 second peer is expected to be available
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"97171fd7-5a90-48e0-9f30-6ab3c966b959","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 peer became unavailable
,ok 411 it was wifi peer
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97171fd7-5a90-48e0-9f30-6ab3c966b959","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 412 we found peer again
,ok 413 it was wifi peer
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"97171fd7-5a90-48e0-9f30-6ab3c966b959","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 414 peer became unavailable
,ok 415 it was wifi peer
,# teardown
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6ab3ed20-5272-40ac-ad00-a27cb46cf20f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 416 error should be null
,ok 417 error should be null
,# setup
,ok 418 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-27 09:43:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 419 error should be null
,ok 420 error should be null
,# setup
,ok 421 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-27 09:43:04 - DEBUG thaliMobileNativeWrapper: 'listening 64413'
,2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5d2441c4-58f5-42f2-a495-7b48aa15b4e9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 422 first peer is expected to be available
,2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5dbf363e-4acb-45a1-aeb8-b177d836db50","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 423 second peer is expected to be available
,2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5d2441c4-58f5-42f2-a495-7b48aa15b4e9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 424 peer became unavailable
,2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5dbf363e-4acb-45a1-aeb8-b177d836db50","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 425 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 426 error should be null
,ok 427 error should be null
,# setup
,ok 428 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-27 09:43:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 429 error should be null
,ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-27 09:43:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 432 error should be null
ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26473826-4467-4f45-8e17-6360fd6fff59","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 435 peer discovered first time does not have new address
,2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26473826-4467-4f45-8e17-6360fd6fff59","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 436 address has not been changed
,2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26473826-4467-4f45-8e17-6360fd6fff59","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 437 new port handled correctly
,2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26473826-4467-4f45-8e17-6360fd6fff59","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 438 new host handled correctly
,2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26473826-4467-4f45-8e17-6360fd6fff59","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 439 newAddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
,ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-27 09:43:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 443 error should be null
,ok 444 error should be null
,# setup
,ok 445 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 446 NOT IMPLEMENTED # SKIP
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-27 09:43:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 450 error should be null
ok 451 error should be null
,# setup
,ok 452 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 453 should be equal
,# teardown
,ok 454 error should be null
ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-27 09:43:06 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 457 error should be null
ok 458 error should be null
,# setup
,ok 459 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 460 contains expected properties
ok 461 the same hostAddress
ok 462 the same portNumber
,# teardown
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 463 error should be null
,ok 464 error should be null
,# setup
,ok 465 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 466 contains expected properties
,ok 467 the same hostAddress
,ok 468 the same portNumber
,# teardown
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-27 09:43:07 - DEBUG thaliMobileNativeWrapper: 'listening 64414'
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"416e5f57-fb7c-4012-8adf-fd3a81d41d31","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 472 Got specific error message
,# teardown
,2017-07-27 09:43:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"416e5f57-fb7c-4012-8adf-fd3a81d41d31","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'listening 64415'
,2017-07-27 09:43:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a30b0e83-0a76-4b34-bf2e-f0415b88d3ee","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:a30b0e83-0a76-4b34-bf2e-f0415b88d3ee
,ok 476 native wrapper `disconnect` called once
,ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-27 09:43:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a30b0e83-0a76-4b34-bf2e-f0415b88d3ee","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 478 error should be null
,ok 479 error should be null
,# setup
,ok 480 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-27 09:43:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 481 error should be null
,ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-27 09:43:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 484 error should be null
ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-27 09:43:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 487 error should be null
ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-27 09:43:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 490 error should be null
,ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-27 09:43:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 493 error should be null
,ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-27 09:43:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 496 error should be null
,ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-27 09:43:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'listening 64416'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3C7514AD-FB07-4630-B534-494F5645ED5C
,[ThaliCore] Browser.startListening
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b6029d73-c0cf-4fd4-bea8-cac0bd7fbc0c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"51d979b6-5118-4bef-85eb-1ffef7de99d5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 503 Peer availabilities has one entry for our connection type
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b6029d73-c0cf-4fd4-bea8-cac0bd7fbc0c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"51d979b6-5118-4bef-85eb-1ffef7de99d5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}]'
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}'
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 504 No peers
,ok 505 No peers
,ok 506 No peers
,# teardown
,ok 507 error should be null
,ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-27 09:43:11 - DEBUG thaliMobileNativeWrapper: 'listening 64417'
2017-07-27 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8967ca13-d666-40bd-b261-a6cc20da8644","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 510 1
ok 511 2
,2017-07-27 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6739ce7a-e731-4431-bedc-7ab8b69fba99","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-27 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8967ca13-d666-40bd-b261-a6cc20da8644","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-27, 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6739ce7a-e731-4431-bedc-7ab8b69fba99","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-27 09:43:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:43:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:43:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:43:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 512 error should be null
,ok 513 error should be null
,# setup
,ok 514 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-27 09:43:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 515 error should be null
,ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'listening 64418'
,ok 518 error should be null
,ok 519 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3630E379-CFFE-462E-BB68-4CD97BA5BD0F
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 520 error should be null
,ok 521 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396
,[ThaliCore] Browser.startListening
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
,ok 522 error should be null
ok 523 error should be null
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}]'
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}'
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:43:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 327545E6-9804-4ADB-A8DA-5253B0B8EB0E (syncValue: 0)'
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7855F8AD-79AD-4F93-83C6-37C069A6A92D", generation: 0)
2017-07-27 09:43:13 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7855F8AD-79AD-4F93-83C6-37C069A6A92D","generation":0}]'
2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7855F8AD-79AD-4F93-83C6-37C069A6A92D","generation":0}'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7855F8AD-79AD-4F93-83C6-37C069A6A92D","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-27 09:43:13 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7855F8AD-79AD-4F93-83C6-37C069A6A92D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0)
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","generation":0}]'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","generation":0}'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}]'
2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}'
,2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-27 09:43:14 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:32,7545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,27545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:43:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
,2017-07-27 09:43:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7855F8AD-79AD-4F93-83C6-37C069A6A92D (syncValue: 1)'
2017-07-27 09:43:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "7855F8AD-79AD-4F93-83C6-37C069A6A92D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7855F8AD-79AD-4F93-83C6-37C069A6A92D", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] Session.deinit peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7855F8AD-79AD-4F93-83C6-37C069A6A92D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64424
2017-07-27 09:43:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":64424,}'
,2017-07-27 09:43:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F1A16AEB-67F5-4902-8B82-F7A5D25F38D1 (syncValue: 2)'
2017-07-27 09:43:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] Advertiser: session connected Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [2, 3, 7, 9, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:43:19 - DEBUG testUtils: 'Got response data'
,2017-07-27 09:43:19 - DEBUG testUtils: 'Got end'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
2017-07-27 09:43:20 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}]'
2017-07-27 09:43:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}'
,2017-07-27 09:43:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-27 09:43:20 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C
[ThaliCore] Advertiser: session connected Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] Session.startOutputStream(with:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [2, 3, 7, 9, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64429
,2017-07-27 09:43:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":64429}'
,2017-07-27 09:43:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 327545E6-9804-4ADB-A8DA-5253B0B8EB0E (syncValue: 3)'
,2017-07-27 09:43:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [2, 3, 7, 9, 15, 16, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:43:22 - DEBUG testUtils: 'Got response data'
,2017-07-27 09:43:22 - DEBUG testUtils: 'Got end'
,ok 524 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C
,[ThaliCore] Session.session(_:peer:didChange:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C
[ThaliCore] Session.startOutputStream(with:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [2, 3, 7, 9, 15, 16, 17, 18]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-27 09:43:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7855F8AD-79AD-4F93-83C6-37C069A6A92D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:43:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:43:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withErr,or:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [2, 3, 7, 9, 16, 17, 18]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:32,7545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,27545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:32,7545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,27545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:64429
[ThaliCore] Session.disconnect() peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0) relay removed
,2017-07-27 09:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","generation":0}]'
,2017-07-27 09:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","generation":0}'
,2017-07-27 09:43:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","peerAvailable":false,"generation":null,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:32,7545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,27545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:32,7545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:327545E6,-9804-4ADB-A8DA-5253B0B8EB0E error: max retries exceeded
2017-07-27 09:43:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Connection could not be established","portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3630E379-CFFE-462E-BB68-4CD97BA5BD0F
2017-07-27 09:43:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-27 09:43:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,}})'
2017-07-27 09:43:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:43:32 - DEBUG thaliMobileN,ativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:43:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:43:32 - DEBUG makeInt,o,CloseAllServer: 'closeAll called on server'
ok 525 error should be null
,ok 526 error should be null
,[ThaliCore] Session.deinit peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [2, 3, 7, 9, 16, 17]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] VirtualSocket.deinit vsID:16 [2, 3, 7, 9, 17]
,# setup
,ok 527 ThaliMobile should be stopped
,# test for data corruption
,2017-07-27 09:43:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 528 error should be null
,ok 529 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 530 getPeerIdentifier
,ok 531 getConnectionType
,ok 532 getActionType
,ok 533 getActionState
,ok 534 getPskIdentity
,ok 535 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 536 initial state
ok 537 after start
2017-07-27 09:43:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 538 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 539 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-27 09:43:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 clean kill
ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 542 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 543 forever agent should have it's own destroy method
,ok 544 agent's destroy should be called
ok 545 agent's destroy should not be called again
ok 546 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 547 Entry counter must be 1
,ok 548 Entry exists
,ok 549 Size must be 1
,ok 550 Entry counter must be 2
,ok 551 Entry exists
,ok 552 Size must be 2
,ok 553 Entry counter must be 1
,ok 554 Entry exists
,ok 555 Size must be 3
,ok 556 Entry counter must be 2
,ok 557 Entry exists
,ok 558 Size must be 4
,ok 559 Entry 1_1 should not be found
,ok 560 Entry 1_1 does not exist
,ok 561 Size must be 3
,ok 562 Entry 1_2 should not be found
,ok 563 Entry 1_2 does not exist
,ok 564 Size must be 2
,ok 565 should be equal
,ok 566 Entry 2_1 should not be found
ok 567 Entry 2_2 should not be found
,ok 568 Entry 2_1 does not exist
,ok 569 Entry 2_2 does not exist
,ok 570 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 571 Size must be100
,ok 572 Entries between 20 and MAXSIZE + 20 should exist
,ok 573 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 574 Entries between 6 and MAXSIZE + 4 should exist
,ok 575 Size should be MAXSIZE
,ok 576 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 577 WAITING state entry should not be removed
,ok 578 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 579 Size should be MAXSIZE
,ok 580 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 581 Kill should be called once
,ok 582 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 583 is an agent
,ok 584 enqueue is fine
,ok 585 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 586 is an agent
ok 587 first enqueue is fine
ok 588 is an agent
ok 589 second enqueue is fine
ok 590 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 591 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 592 is an agent
,ok 593 good enqueue
,ok 594 Identity should match
,2017-07-27 09:43:38 - DEBUG testUtils: 'Got response data'
,2017-07-27 09:43:38 - DEBUG testUtils: 'Got end'
,ok 595 Got expected response
,ok 596 Got psk call back
,# teardown
,2017-07-27 09:43:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 597 is an agent
,ok 598 enqueue worked
ok 599 is an agent
ok 600 enqueue 2 worked
ok 601 enqueue is not available when stopped
ok 602 start action is killed
ok 603 killed action is still killed
,ok 604 enqueued action when stopped is killed
,ok 605 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 606 good start
ok 607 good enqueue
ok 608 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 609 null arg
,ok 610 wrong arg type
,ok 611 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 612 good enqueue
ok 613 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 614 good enqueue
ok 615 2nd good enqueue
ok 616 we are in the pool
ok 617 We are out of the pool
ok 618 Action was killed
ok 619 The original kill was called too
ok 620 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 621 good enqueue
ok 622 first kill
ok 623 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 624 1st good enqueue
,ok 625 2nd good enqueue
,ok 626 1st action is in the pool
,ok 627 2nd action is in the pool
,ok 628 1st action is out of the pool
,ok 629 2st action is out of the pool
,ok 630 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-27 09:43:42 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 631 Got right error
,ok 632 Start should not be called
,ok 633 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-27 09:43:43 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 634 Got right error
,ok 635 Start should not be called
,ok 636 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 637 Got null
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 638 is an agent
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 639 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 640 Got Null
,ok 641 Got another null
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 642 is an agent
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 643 is an agent
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 644 Action 1 killed at least once
,ok 645 Action 1 went first
,ok 646 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication, response with no error!'
ok 647 should have gotten null
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activit,y time out - noActivityTimeOut'
ok 648 Should have stopped nicely
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startErr,or: eeeek! - failureButNotAvailable'
ok 649 Still looking for null
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 650 Yup, another null
,ok 651 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 652 Null 1
,ok 653 (unnamed assert)
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 654 is an agent
,ok 655 Null 3
,ok 656 Replication not yet called
,ok 657 Notification 2 not yet called
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 658 is an agent
,ok 659 Notification went first
,ok 660 Notification 2 not called yet
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 661 is an agent
,ok 662 Notification finished
,ok 663 Replication finished
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 664 is an agent
,ok 665 First does not throw
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 666 is an agent
,ok 667 Second does not throw
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 668 is an agent
,ok 669 first ok
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 second ok
,ok 672 third ok
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-27 09:43:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-27 09:43:46 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 673 peerIdentifier should match
,ok 674 generation should match
,ok 675 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 676 good beacon
,ok 677 good preAmble
,ok 678 public keys match!
,ok 679 must return null after successful call
,ok 680 Once start returns the action should be in KILLED state
,# teardown
,2017-07-27 09:43:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-27 09:43:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-27 09:43:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 681 Response should be NETWORK_PROBLEM
,ok 682 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-27 09:43:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 683 Resolution should be BAD_PEER
,ok 684 correct error message
,# teardown
,2017-07-27 09:43:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 685 Call start once
,ok 686 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 687 must return null after successful call.
,# teardown
,2017-07-27 09:43:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 688 Should be Killed
ok 689 Start after killed
,# teardown
,2017-07-27 09:43:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 690 Should be KILLED
ok 691 must return null after successful kill
,# teardown
,2017-07-27 09:43:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-07-27 09:43:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 694 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 695 must return null after successful call
,# teardown
,2017-07-27 09:43:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-27 09:43:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 696 Should be NETWORK_PROBLEM caused closing server socket
,ok 697 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 698 Should be NETWORK_PROBLEM caused closing client socket
,ok 699 Should be Could not establish TCP connection
,# teardown
,2017-07-27 09:43:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 700 publicKeysToNotify cannot be null
,ok 701 ecdh for local device cannot be null
,ok 702 milliseconds cannot be less than 0
,ok 703 milliseconds cannot be 0
,ok 704 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 705 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 706 should be equal
,ok 707 should be equal
,ok 708 (unnamed assert)
,ok 709 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 710 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 711 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 712 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 713 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 714 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 715 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 716 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-07-27 09:44:03 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 717 should be equal
,ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 719 right number of calls to address book
ok 720 good preAmble
,ok 721 good unencryptedKeyId
,ok 722 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 723 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 724 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 725 Matching numbers
,ok 726 We have an entry!
,ok 727 keys match
,ok 728 secrets match
,ok 729 We have an entry!
,ok 730 keys match
,ok 731 secrets match
,ok 732 We have an entry!
,ok 733 keys match
,ok 734 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 735 Streams have same length
,ok 736 matching size
,ok 737 keys match
,ok 738 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 739 should be equal
,ok 740 peerDictionalty contains 2 peers
ok 741 bluetooth peer's notification has correct connection type
ok 742 tcp peer's notification has correct connection type
,2017-07-27 09:44:08 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-27 09:44:08 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-27 09:44:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 743 notification peer dictionary contains exactly 1 peer
,2017-07-27 09:44:08 - WARN thaliNotificationClient: 'peer is not available'
,ok 744 notification peer dictionary does not contain any peers
,2017-07-27 09:44:08 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-27 09:44:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 745 entry exists
,ok 746 entry is resolved
,# teardown
,2017-07-27 09:44:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 747 Action should be KILLED
,ok 748 Peer state should be RESOLVED
,# teardown
,2017-07-27 09:44:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 749 hostAddress must match
,ok 750 portNumber must match
,ok 751 suggestedTCPTimeout must match
,ok 752 connectionType must match
,ok 753 peerIDs must match
,# teardown
,2017-07-27 09:44:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 754 Correct error
,# teardown
,2017-07-27 09:44:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 755 hostAddress must match
,ok 756 portNumber must match
,ok 757 suggestedTCPTimeout must match
,ok 758 connectionType must match
,ok 759 peerIds must match
,# teardown
,2017-07-27 09:44:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-27 09:44:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 760 action should be resolved with NETWORK_PROBLEM error
,2017-07-27 09:44:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 761 action should be resolved with NETWORK_PROBLEM error
,2017-07-27 09:44:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-27 09:44:13 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 763 action should be resolved with NETWORK_PROBLEM error
,ok 764 correct number of requests
,ok 765 correct number of failures
,ok 766 correct final peer state
,# teardown
,2017-07-27 09:44:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-27 09:44:16 - WARN thaliNotificationClient: 'peer is not available'
2017-07-27 09:44:16 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 peerDictionary should become empty
,# teardown
,2017-07-27 09:44:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-27 09:44:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 768 failed with expected error
ok 769 peer state should be RESOLVED
,# teardown
,2017-07-27 09:44:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-27 09:44:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 First action failed
,ok 771 second action killed
# teardown
,2017-07-27 09:44:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 772 secrets are equal
ok 773 Public key matches with the server key
,ok 774 hostAddress must match
,ok 775 portNumber must match
,ok 776 suggestedTCPTimeout must match
,ok 777 connectionType must match
,# teardown
,2017-07-27 09:44:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 778 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 779 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 780 All entries should be expired after 1 second
# teardown
,2017-07-27 09:44:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 781 All keys need to be available in the cache
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-27 09:44:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 783 Size of the cache should be 2
ok 784 Cache doesn't contain dictionary1
,ok 785 Size of the cache should be 1
ok 786 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-27 09:44:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 787 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 788 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-27 09:44:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 789 StartUpdateAdvertisingAndListening should not be called
,ok 790 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 791 no error
,ok 792 should be 204
,# teardown
,2017-07-27 09:44:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-27 09:44:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 794 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-27 09:44:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 795 no error
,ok 796 should be 200
,ok 797 should be equal
,ok 798 should be equal
,ok 799 (unnamed assert)
,ok 800 no error
,ok 801 should be 204
,# teardown
,2017-07-27 09:44:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 802 error should be null
,ok 803 should be 204
# teardown
,2017-07-27 09:44:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 804 should be 404
,# teardown
,2017-07-27 09:44:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 805 equal keys
ok 806 not equal connection type
ok 807 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-27 09:44:27 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 808 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 809 second cleared dictionary
,2017-07-27 09:44:28 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 810 First start and on called correctly
,ok 811 First stop and removeListener called correctly
,ok 812 first action kill called
,ok 813 second action kill called
,ok 814 first cleared dictionary
,ok 815 first cleared pool
,ok 816 second cleared dictionary
,ok 817 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 818 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-27 09:44:29 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 819 listener has been set
,ok 820 peer dictionary has expected number of entries
,ok 821 Dictionary and pool have same action
,ok 822 ads match
,ok 823 PouchDB matches
,ok 824 DB Names match
,ok 825 public keys match
,ok 826 peer dictionary has expected number of entries
,ok 827 Dictionary and pool have same action
,ok 828 ads match
,ok 829 PouchDB matches
,ok 830 DB Names match
,ok 831 public keys match
,2017-07-27 09:44:29 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 832 start called once
,ok 833 One entry left
,ok 834 Dictionary and pool have same action
,ok 835 Start never called
,ok 836 Kill called once
,ok 837 no entries left
,ok 838 Third action is dead
,ok 839 peer dictionary has expected number of entries
,ok 840 Dictionary and pool have same action
,ok 841 ads match
,ok 842 PouchDB matches
,ok 843 DB Names match
,ok 844 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-27 09:44:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-27 09:44:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 845 right error
,# teardown
,2017-07-27 09:44:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 846 right error
,# teardown
,2017-07-27 09:44:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 847 Got error as expected
,# teardown
,2017-07-27 09:44:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 848 Got error as expected
,# teardown
,2017-07-27 09:44:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-27 09:44:32 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-27 09:44:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-27 09:44:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-27 09:44:35 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-27 09:44:35 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-27 09:44:37 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 850 should be equal
ok 851 All tests passed!
,# teardown
,2017-07-27 09:44:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-27 09:44:39 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-27 09:44:40 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-27 09:44:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-27 09:44:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-27 09:44:43 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-27 09:44:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-27 09:44:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 854 action should be killed
,ok 855 Error should be timed out
,ok 856 No doc found
,# teardown
,2017-07-27 09:44:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-27 09:44:47 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-27 09:44:48 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 857 should be equal
,2017-07-27 09:44:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-27 09:44:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 858 action should be killed
,ok 859 Error should be timed out
,# teardown
,2017-07-27 09:44:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 860 socket hung up
,# teardown
,2017-07-27 09:44:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 861 same getPeerAdvertisesDataForUs
,ok 862 Same pouchdB
,ok 863 same localDbName
,ok 864 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-27 09:44:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-27 09:44:53 - DEBUG thaliMobileNativeWrapper: 'listening 64565'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] Browser.startListening
,2017-07-27 09:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "31FA610D-63B5-4DE0-AB0D-AEAF0401113A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:31FA610D-63B5-4DE0-AB0D-AEAF0401113A
,2017-07-27 09:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] Advertiser: session connected Peer(uuid: "31FA610D-63B5-4DE0-AB0D-AEAF0401113A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0)
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3","generation":0}]'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3","generation":0}'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-27 09:44:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3 (syncValue: 4)'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Advertiser: session connected Peer(uuid: "31FA610D-63B5-4DE0-AB0D-AEAF0401113A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A199F954-C675-4B5C-AE40-A799E390F491 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31FA610D-63B5-4DE0-AB0D-AEAF0401113A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0 state: notConnected -> connecting
2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4B93F383-00C0-458F-9A5F-89AA952BC1DA","generation":0}]'
2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4B93F383-00C0-458F-9A5F-89AA952BC1DA","generation":0}'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4B93F383-00C0-458F-9A5F-89AA952BC1DA","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:44:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4B93F383-00C0-458F-9A5F-89AA952BC1DA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64568
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,2017-07-27 09:44:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":64568}'
,2017-07-27 09:44:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4B93F383-00C0-458F-9A5F-89AA952BC1DA (syncValue: 5)'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A199F954-C675-4B5C-AE40-A799E390F491 state: connecting -> connected
,2017-07-27 09:44:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,9 [2, 3, 7, 9, 17, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [2, 3, 7, 9, 17, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:19 [2, 3, 7, 9, 17, 20]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [2, 3, 7, 9, 17, 20, 21]
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.startOutputStream(with:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [2, 3, 7, 9, 17, 20, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:44:57 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [2, 3, 7, 9, 17, 20, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] Session.session(_:peer:didChange:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] Session.session(_:peer:didChange:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 25, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28]
[ThaliCore] BrowserRelay.didOpenVi,rtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 30, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 33]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:44:58 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:33 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,5 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,6 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
,[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSock,etDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:35 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 36, 37]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withErr,or:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64589
,2017-07-27 09:45:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":64589}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] Session.startOutputStream(with:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,9 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 37, 38]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 37]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 37, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] Session.startOutputStream(with:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 37, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.deinit vsID:41 [2, 3, 7, 9, 17, 20, 21, 22, 23, 24, 26, 27, 28, 29, 31, 32, 34, 37, 40]
,2017-07-27 09:45:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-27 09:45:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [2, 3, 7, 9, 17, 20, 21, 23, 24, 26, 27, 28, 29, 31, 32, 34, 37, 40]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [2, 3, 7, 9, 17, 20, 21, 23, 26, 27, 28, 29, 31, 32, 34, 37, 40]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:28
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [2, 3, 7, 9, 17, 20, 21, 23, 26, 27, 29, 31, 32, 34, 37, 40]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [2, 3, 7, 9, 17, 20, 21, 23, 26, 27, 31, 32, 34, 37, 40]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
,[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [2, 3, 7, 9, 17, 20, 23, 26, 27, 31, 32, 34, 37, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [2, 3, 7, 9, 17, 20, 26, 27, 31, 32, 34, 37, 40]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualS,ocket.closeStreams() vsID:31
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [2, 3, 7, 9, 17, 20, 27, 31, 32, 34, 37, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:,nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [2, 3, 7, 9, 17, 20, 27, 32, 34, 37, 40]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:45:00 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [2, 3, 7, 9, 17, 20, 27, 32, 34, 37, 40, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
,[ThaliCore] Session.startOutputStream(with:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [2, 3, 7, 9, 17, 20, 27, 32, 34, 37, 40, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] AdvertiserRelay.didC,loseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [2, 3, 7, 9, 17, 20, 27, 32, 34, 37, 40, 42]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [2, 3, 7, 9, 17, 20, 27, 32, 34, 37, 40, 42, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
,[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [2, 3, 7, 9, 17, 20, 32, 34, 37, 40, 42, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected,
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:32 [2, 3, 7, 9, 17, 20, 34, 37, 40, 42, 44]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [2, 3, 7, 9, 17, 20, 37, 40, 42, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [2, 3, 7, 9, 17, 20, 37, 40, 42, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [2, 3, 7, 9, 17, 20, 40, 42, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDi,sconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] Session.startOutputStream(with:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [2, 3, 7, 9, 17, 20, 40, 42, 44, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [2, 3, 7, 9, 17, 20, 40, 42, 44, 45, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [2, 3, 7, 9, 17, 20, 40, 42, 44, 45, 47]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [2, 3, 7, 9, 17, 20, 40, 42, 44, 45, 47, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] VirtualSocket.deinit vsID:47 [2, 3, 7, 9, 17, 20, 40, 42, 44, 45, 48]
,2017-07-27 09:45:02 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] Session.startOutputStream(with:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,9 [2, 3, 7, 9, 17, 20, 40, 42, 44, 45, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [2, 3, 7, 9, 17, 20, 40, 42, 44, 45, 48]
,2017-07-27 09:45:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-27 09:45:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [2, 3, 7, 9, 17, 20, 42, 44, 45, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:42 [2, 3, 7, 9, 17, 20, 44, 45, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:44 [2, 3, 7, 9, 17, 20, 45, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:48 [2, 3, 7, 9, 17, 20, 45]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] Session.startOutputStream(with:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,0 [2, 3, 7, 9, 17, 20, 45, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [2, 3, 7, 9, 17, 20, 45]
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C
,[ThaliCore] Session.deinit peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C
[ThaliCore] AdvertiserRelay.deinit
,2017-07-27 09:47:55 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-27 09:47:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:47:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4,C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4,C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4,C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4,C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4,C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-27 09:54:53 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07,-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGG,ER result: passed - enqueue and run in order'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and en,queueAtTop'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously',
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return err,or if we get called on iOS'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure termin,ateListener is return error if we get called on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-27 09:54:53 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,not ok 865 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-27 09:55:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4,C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4,C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4,C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4,C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C2,2-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86504F6B-55F5-4C22-A92A-865D99CF33AE/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
