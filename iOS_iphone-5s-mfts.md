#### Test 11335185196ab692_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/47B7A7B1-2EA9-4239-BDBA-ECBD7F940F19/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/47B7A7B1-2EA9-4239-BDBA-ECBD7F940F19/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65301"
,(lldb)     command script import "/tmp/47B7A7B1-2EA9-4239-BDBA-ECBD7F940F19/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
JXcore engine is started
,2017-07-13 08:31:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:31:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:31:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:31:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:31:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:31:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:31:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3238527A-CFFE-40A2-9FA9-CC8FD6F0A092", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3238527A-CFFE-40A2-9FA9-,CC8FD6F0A092
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:913DADAC-6DE9-4363-A556-64BA537F3FC9
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:657299CE-,2F08-473C-B614-1EC3E9F5DF28
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FC1A405B-A01F-42A8-8927-AE19BCDACFD3", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:FC1A405B-A01F-42A8-8927-AE19BCDACFD3
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FC1A405B-A01F-42A8-8927-AE19BCDACFD3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FC1A405B-A01F-42A8-8927-AE19BCDACFD3", generation: 0)
AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvaila,bilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-13 08:31:17 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.684079051017761
,2017-07-13 08:31:17 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-07-13 08:31:17 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FC1A405B-A01F-42A8-8927-AE19BCDACFD3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FC1A405B-A01F-42A8-8927-AE19BCDACFD3", generation: 0)
,2017-07-13 08:31:20 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-13 08:31:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-13 08:31:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-13 08:31:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-13 08:31:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-13 08:31:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-13 08:31:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-13 08:31:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-13 08:31:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-13 08:31:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-13 08:31:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-13 08:31:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-13 08:31:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-13 08:31:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-13 08:31:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-13 08:31:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-13 08:31:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-13 08:31:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-13 08:31:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-13 08:31:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-13 08:31:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-13 08:31:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-13 08:31:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-13 08:31:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-13 08:31:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-13 08:31:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-13 08:31:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-13 08:31:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-13 08:31:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-13 08:31:24 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-13 08:31:24 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-13 08:31:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E5,1-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E5,1-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:31:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E5,1-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:31:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E5,1-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:31:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:49 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-13 08:31:49 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-13 08:31:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-13 08:31:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-13 08:31:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-13 08:31:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-13 08:31:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-13 08:31:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-13 08:31:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-13 08:31:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,ok 33 second
,ok 34 secondPromise - in then
,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
,# teardown
,# setup
,# queues handled independently
,ok 40 all short operations completed before the long resolves
,# teardown
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
,2017-07-13 08:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-13 08:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-13 08:32:02 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-13 08:32:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-13 08:32:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:07DF4AB8-0895-43D0-A004-4D4A441FA36A
[ThaliCore] Browser.startListening
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 08:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {",discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BF7DDFE0-638E-44BE-AB48-972C4C025465
[ThaliCore] Browser.startListening
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 08:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 08:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 08:32:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "81CDB642-0056-4101-A2F0-3B7F1AB524E4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:81CDB642-0056-4101-A2F0-3B7F1AB524E4
2017-07-13 08:32:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:12, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
,2017-07-13 08:32:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdv,ertising()
2017-07-13 08:32:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:32:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 76 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:32:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:32:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C94ED78F-A106-4084-85CD-2064E56D110A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C94ED78F-A106-4084-85CD-2064E56D110A
,2017-07-13 08:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C94ED78F-A106-4084-85CD-2064E56D110A", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:C94ED78F-A106-4084-85CD-2064E56D110A
,2017-07-13 08:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:32:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:32:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:19 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:32:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9
2017-07-13 0,8:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E39A5026-F476-42B1-884C-9E361C2BA64B
[Thali,Core] Browser.startListening
,2017-07-13 08:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 08:32:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 08:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AEF459FD-A12E-4767-8E65-58B69FA8326B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AEF459FD-A12E-4767-8E65-58B69FA8326B", generation: 0)
,ok 88 peers must be an array
ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'd,iscoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndList,e,ning in teardown
,# setup
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9687EBC4-01F9-4F14-9B77-F38A65897F0D
2017-07-13 0,8:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:542410F8-E47D-4D09-9B3D-AB8970C059FA
[ThaliCore] Browser.startListening
2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 08:32:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
2017-07-13 08:32:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BFAB98DA-9CF3-43B9-91FE-CA3032A13861","generation":0}'
,2017-07-13 08:32:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BFAB98DA-9CF3-43B9-91FE-CA3032A13861 (syncValue: fWSIDWp2IsgP6BJlb5dlXheViR0qFCjA)'
,2017-07-13 08:32:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
[ThaliCore] Session.init(sess,ion:identifier:connected:notConnected:) peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 08:32:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F2E49934-D5B4-44BA-830F-E06FF747D0D3","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49776
2017-07-13 08:32:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fWSIDWp2IsgP6BJlb5dlXheViR0qFCjA","error":null,"portN,umber":49776}'
2017-07-13 08:32:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fWSIDWp2IsgP6BJlb5dlXheViR0qFCjA', error: 'null', listeningPort: '49776''
,2017-07-13 08:32:39 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:38F26A7C-2372-4A66-9872-EC117B984840
[ThaliCore] Advertiser: session connected Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:38F26A7C-2372-4A66-9872-EC117B984840 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:38F26A7C-2372-4A66-9872-EC117B984840
,[ThaliCore] Session.session(_:peer:didChange:) peer:38F26A7C-2372-4A66-9872-EC117B984840 state: connecting -> connected
,2017-07-13 08:32:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:32:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:32:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:32:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:32:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49776
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:38F26A7C-2372-4A66-9872-EC117B984840 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:38F26A7C-2372-4A66-9872-EC117B984840
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:38F26A7C-2372-4A66-9872-EC117B984840
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:61756926-9537-4B4F-AF8E-72C7D7AF849C
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:32:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:32:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 102 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6D36D22C-02F7-4FC8-A4F8-7E90F96EA124
,[ThaliCore] Browser.startListening
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 08:32:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 08:32:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BFAB98DA-9CF3-43B9-91FE-CA3032A13861","generation":0}'
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BFAB98DA-9CF3-43B9-91FE-CA3032A13861 (syncValue: 8E0ZVdYXA7YWiH2njR1MWwzGpOtHPELA)'
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F2E49934-D5B4-44BA-830F-E06FF747D0D3","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
2017-07-13 08:32:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0D279F4F-B96C-44A0-AAFA-099C9029E9D0","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0)
2017-07-13 08:32:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B5FFC2F2-DB79-4AE2-90E5-D9B68505283E","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", genera,tion: 0)
2017-07-13 08:32:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8E0ZVdYXA7YWiH2njR1MWwzGpOtHPELA","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:32:54 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '8E0ZVdYXA7YWiH2njR1MWwzGpOtHPELA', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:32:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"BFAB98DA-9CF3-43B9-91FE-CA3032A13861","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:32:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,08:32:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BFAB98DA-9CF3-43B9-91FE-CA3032A13861","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:32:54 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:32:54 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:32:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F2E49934-D5B4-44BA-830F-E06FF747D0D3 (syncValue: PJofiDx,NqdkQeO9uIZRLhUs1u9ndVTA6)'
2017-07-13 08:32:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F2E49934-D5B4-44BA-830F-E06FF747D0D,3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AE4A6AC6-7D4D-4E38-A079-A38EAAF9B9D7
[ThaliCore] Advertiser: session connected Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AE4A6AC6-7D4D-4E38-A079-A38EAAF9B9D7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", genera,tion: 0)
2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PJofiDxNqdkQeO9uIZRLhUs1u9ndVTA6","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:32:59 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'PJofiDxNqdkQeO9uIZRLhUs1u9ndVTA6', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdent,ifier":"F2E49934-D5B4-44BA-830F-E06FF747D0D3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,08:32:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F2E49934-D5B4-44BA-830F-E06FF747D0D3","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:32:59 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:32:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0D279F4F-B96C-44A0-AAFA-099C9029E9D0 (syncValue: cZscdzB,U0oAhTdx14eLlzRMHhQ914jS2)'
2017-07-13 08:32:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42D718ED-D232-44C7-8DDC-484B16BA1C84
[ThaliCore] Advertiser: session connected Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42D718ED-D232-44C7-8DDC-484B16BA1C84 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AE4A6AC6-7D4D-4E38-A079-A38EAAF9B9D7
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE4A6AC6-7D4D-4E38-A079-A38EAAF9B9D7 state: connecting -> connected
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AE4A6AC6-7D4D-4E38-A079-A38EAAF9B9D7
[ThaliCore] Session.startOutput,Stream(with:) peer:AE4A6AC6-7D4D-4E38-A079-A38EAAF9B9D7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42D718ED-D232-44C7-8DDC-484B16BA1C84
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:42D718ED-D232-44C7-8DDC-484B16BA1C84 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49782
2017-07-13 08:33:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cZscdzBU0oAhTdx14eLlzRMHhQ914jS2",,"error":null,"portNumber":49782}'
2017-07-13 08:33:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cZscdzBU0oAhTdx14eLlzRMHhQ914jS2', error: 'null', listeningPort: '49782''
,Connecting to the localhost:49782
,Connected to the localhost:49782
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42D718ED-D232-44C7-8DDC-484B16BA1C84
[ThaliCore] Session.startOutputStream(with:) peer:42D718ED-D232-44C7-8DDC-484B16BA1C84
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 2, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Server data flushed'
,ok 104 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [1, 2]
# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 08:33:03 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 08:33:03 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 08:33:03 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
2017-07-13 08:33:03 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 [2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 08:33:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE4A6AC6-7D4D-4E38-A079-A38EAAF9B9D7 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:42D718ED-D232-44C7-8DDC-484B16BA1C84
[ThaliCore] Session.deinit peer:42D718ED-D232-44C7-8DDC-484B16BA1C84
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49782
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CBE4BA45-6080-444B-B5A9-545B9189CA71
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:33:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 107 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5
,[ThaliCore] Browser.startListening
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0)
2017-07-13 08:33:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B5FFC2F2-DB79-4AE2-90E5-D9B68505283E","generation":0}'
2017-07-13 08:33:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B5FFC2F2-DB79-4AE2-90E5-D9B68505283E, (syncValue: WdZYye1q1cKiRR2K8joZzJQEYBssHivP)'
2017-07-13 08:33:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0) new relay
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0
[T,haliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-13 08:33:04 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0D279F4F-B96C-44A0-AAFA-099C9029E9D0","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
2017-07-13 08:33:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A385ACA9-6BE4-4961-9C6A-7F8665F19C7C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08B6D133-C3D4-4338-B019-A18C4389675A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", generation: 0)
2017-07-13 08:33:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"08B6D133-C3D4-4338-B019-A18C4389675A","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0)
[ThaliCore] Session.disconnect() peer:B5FFC2F2-DB7,9-4AE2-90E5-D9B68505283E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", genera,tion: 0)
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WdZYye1q1cKiRR2K8joZzJQEYBssHivP","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'WdZYye1q1cKiRR2K8joZzJQEYBssHivP', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"B5FFC2F2-DB79-4AE2-90E5-D9B68505283E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,08:33:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B5FFC2F2-DB79-4AE2-90E5-D9B68505283E","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:33:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0D279F4F-B96C-44A0-AAFA-099C9029E9D0 (syncValue: pKkjgze,r9tOaC4aOcZRwYmo0PjWQPw3G)'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] Session.disconnect() peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
,2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pKkjgzer9tOaC4aOcZRwYmo0PjWQPw3G","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:33:15 - DEBUG thaliMobileNativeTestUtils: 'Got mul,tiConnectResolved -syncValue: 'pKkjgzer9tOaC4aOcZRwYmo0PjWQPw3G', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0D279F4F-B96C-44A0-AAFA-099C9029E9D0","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:15 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0D279F4F-B96C-44A0-AAFA-099C9029E9D,0","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 08:33:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A385ACA9-6BE4-4961-9C6A-7F8665F19C7C (syncValue: HJLEtyQFDdTXDdSJS0WPew6az1EUgFIt)'
,2017-07-13 08:33:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF
[ThaliCore] Advertiser: session connected Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49794
2017-07-13 08:33:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HJLEtyQFDdTXDdSJS0WPew6az1EUgFIt",,"error":null,"portNumber":49794}'
2017-07-13 08:33:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HJLEtyQFDdTXDdSJS0WPew6az1EUgFIt', error: 'null', listeningPort: '49794''
,Connecting to the localhost:49794
Connecting to the localhost:49794
,Connecting to the localhost:49794
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] BrowserRelay.createVirtual,Socket(with:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] Session.startOutputStream(with:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
Connecte,d to the localhost:49794
,Connected to the localhost:49794
,[ThaliCore] Session.startOutputStream(with:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
Connected to the localhost:49794
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 4, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [2, 5, 6]
,ok 112 got the same data back
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [2, 5]
,ok 114 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF
,[ThaliCore] Session.session(_:peer:didChange:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF
[ThaliCore] Session.startOutputStream(with:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7, [2, 5, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF
[ThaliCore] Session.startOutputStream(with:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 5, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF
[ThaliCore] Session.startOutputStream(with:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [2, 5, 7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server received all data: gVvVKXO0G20LVA4BV1ApOUZLyyHjYeZSw2THvZ4ojbBTQjcseljbj25e70LKZvZmcUyvWX0L9aF7YMUTOJofUoyfaobKAMc8bdn6X9WbMYZNc97dJ2tr0mlLgiYheDJ5lINH92SfQ2Apcu7ux3v8ty2j9ZvRlVEPBPCOdPtZJI6GdCRsvF,8pMicQsVVzuP1JqKLLLJkmNuhbeN7HXM3GZ6e567t1RtHwFVgKCururfm8u6fDS1YOV5sfvPgghRdrcBpvl3h60xFS6YSXsKmdrZ1hqoFtdPgYj1Gal9GSFcwgFkIWInTNkA8E15pJBJzr3P5ZHNFMunwWROEp1sMo9stR9pUfvLJwavNW1yw73dnRdpuMjYIdQgJmYMJFEVCftAwLBiSZt6IDBWAv2zYm7O10RNRDtTzF66syfT4eLDd3J0oO8Z,2bhFwfCPzTe5tB7dyQVb4VenuKDz6YBbrpn2k9HQkuSMmydcRTHpvtT86iWOKMIMR4UnMEOwbA5vToVDB31UqoQmmzxtsC4fQCO51gFurMkLvdDNpTgGrJ3xqDpDLe0KKoBUkQCyGZVL12xT62dAmEGng58xQnTAjwSrDsQ1VSWoW4iVlPg98iBIWcBPwu4RhUZmFJI3Vlgq3iYunXWgqyEnlQL1ZsmDq6E9y5yXeBiYt8y7nlRQmfREI5JfY6fI,shoLSIwOkQLaPZCxt3CMGHBoF7dYoEzpHwaazVz5IS8Puu8XSokd24Hq2KeBtQl0WbsDvHD4DLMpYmUDkOmSX5Hx6eKMNpEi9yKBGHf9H30IxKqbh7utl7hjvTDJRTUkKhsK4qtiDZKgD16oBeC2HEngqngVPVQpMbjg5HlxgR2wiYJXerAF0yngPllbsdnEuIi9GYK223dyCi6ZrMQq3vcBkJWAoF6bkxaPwj4QI56CKGV3nq1dU6kculohVzuB,J3H4fzXliZ4TEnX85eYizgT0oAyMTT1IHLKHgLHFnE42AWBAS0RDJPbStsmmQylHcnEgXkW2kjKPYpDUFOVKcqyrIXsx3eEFwNZ1gXOa73LcyGxeDfiExkQgtlEDVUmjNTIVm2AHhQSUfJdFWWvQ5hD58wWLBzYtw4stUjuuvw6YhKA7OcVFrNskEdF5pg7D1oRFTWtAK7hsDPDCgbqhcCp1Ud2VuDxXWpG4uLQESH0BnDMm5wfkXtsPCb0tXgJw,2s7of4f4jTaz1UiejBgYFaUFwoPYJyMqkWGdXsYkNCKPbAXuRvlrzUvIVaFVWGg4UGvXry3J76DfFQL91EaCT1SFgwM7Z1DklyiJzjOFHLdj8pECbc79V2rClHuRPQVrob4cx9IzaS4F6kJF5KPVecO5cz23RCBuWaz4Apcuv7iyvw21QGFdG8XCkgrcihZMyf0534S3cCSVtTtEyPGWL5EtRrEIPqUUnNDd7HwKdAfAd2mdSMto5Dc5VyO2OPEr,nIHcQP7Dkqupm2IivXW4sirbI2epwtPh2RYUfR4snIWYvfOXaoz2VxTjwVXPDYjSR2pC300fwMvisj9EB7ktpOC5eMiGvE2OzzgIeH27kGsiPXnkyOxC5F3G9iLP0EDp96iLnNkIA1pblN2NOHHmcFpLzSCTd4SjkRH2PDvdvOjGPEfCo6lybgh4lCjhqOS6l8AMBA0oKrJVnzPgrwHNgC04ETfg19VDn3ngJyr16c99xKDnTpT2gmXKWfj1Loh6,xT5iHGbMVBoC7NcBEJVVkhyaPp3ECvIBkqtZu2W11Sd51Nz4tfEYPdIN3719lnsPJmwWoeIh9bENHqq2E7hSUGgyuahQFhqhy6jvOJxQX182hZmqkoVz1zU3FSZw5QMdUYnOqR1sormxqkRF17S77tcqAMzhboJjoisOAPNcf2ODKcGh7vzJssCqcW1pWHNfzybBv5BJf7EqG1WSw3cyT9Dzd7RuoOEnAwRLDLq8X83wI0Wh8OaD3NBXp6cHrRNi,EqsIRVYXVWV7sVKoOtVdceRoAqqagllF49QL2TiLt7GFxa9LSXVEeWfqR9HQq7nd02pibIlZz6jkqUWwIOHe1OOVaAPoLYJ3PSEuGzqX1e7HJuGNB24jZNGNLotUvnsgFdbT1UAYN4HFXe263HqszqsdL8C98TMvBLMmTngGx7acmTOyWsYR3FOuBe7FbRqxAgN4VHG7PFhpQBxhaoedrekrnDZvTVHQUk3FyYtNpm4BUBUTo5TJOsgZ1AQEKbCS,np1wRNHgglea7k3pk6ngfohVE93gjj7Di7itbeJyOOuFmIAp2e2zqg6ONz31Q5uFZZkIJoVTbE5DMjmEg7leOKGDTFzGqFHAC6kzhU6qKjwo8xEpfzxmR0tXCbec2fuSSVLOoT8UifVe5BhZpOXcQlC9kGtLkL02ZceAhvqs4LtkLjsVGUDTbd2q1GufnLCWox5Ish8NzWjyzley7iuI4z3sDMc0fjS263E7gfGTnmVmOM5CGPStb5pFbTOwbs45,9cJ1vYDcH9nryXONMU7enQodTWNqvSELxxOWraiA8CW0izL8R8kcXtN59Hw1J1FnDdRd8WE1m265saOFBBhNMsup241nSqXMokcx2LxkMVWJyHePKhMUr6b1MYzexgj3flAJqgmD4ZyPzOktAxLwVkX86VRTZ6HeO6gdIaPkqju8NlGCXjCb9O2Um6mTsWylURpaWnpf3T7Pa7RdnzMNcHmQPLFO4QYrSCxKyrsdG5a3U85ULe9tKCkLBfH0JPp6,0L26no30dHeItH8PQrfVyHZozb5pUK9hkEzDbtRNSf9XyR8gkjqV0AaKvaeySkk5p7nTa4h94BZJw0O7eDE3hFFLMmWMu3Aaqgxvtg6hSOcaH5TsjHcpQjxGbvtk8rcfDtQVXeFvOKMhuBCZH1yaKtnrGhaz820IyGQKboCstPCCsHkSfC0PVSV7KuZ3bvVnTG79RrNZoTuMuH0oQAHNCxzsVqGtYG7EAE4ozQrjje1OtIjXSApWzMcJf5xhKADr,nSvk9FfZNPx0BFApS1K6bYNRI05j8Wa2zqwgRcFZPV1N81dtsJLrcJlCQVyB1IhwCQPqEDUO2tIlpnrwKlUq61NSeDgYXHlKQCXZ1MpuHzFBsStDlx8M8Tc5ql3BMSbjX7PUUemYQAhSSRjbV42Gdk5MUpsXYbrPNnSPJ2uwV45GCT9u388JaxEPLzGIhDMlh6ctkRDihFHBLuaPp8B9bHf18sAFZdIRGSmnshvXWkPRupZpSB6KALhjC7S6HfWX,kgiWgCMLs0E7130v8grSqflqxt8cd36bO93aO8HhNjCjUWplQAKwl6abMNcQH1ICufXmeNklSuozAKhVdSgSmGTHb5KeU4lDTpfH58GR8YG82bKK8dbMK7xjEgcTvSwCKfFM8Wpd3cGngazk2PHkIksndRXekwUOTLVLc6XWumzSGPaCA74Uwjhcnw0FindeN9vXCErKguImvFiSYPaaAVMLulv7lzBZJI0lPcuFiC9YtmtoPxwmNeXOgVBAEUy6,iG6EvYKJOOirhDqrCabKLhxJ5qcuav1MsUVlv9VieQ9AmePEmSebHTLMp1duiGhdN2yn0Ety4fN7uRYd3J3kVawK9dRLpiSmvxLJBEnDWeutby4swru8lKpJIeCWLbCTOB1GuNABZqcjE40GB5H65R9p8W0Y1l97Sa9QcPkI6weSYvTmieFgs9LNWn7iuELFfJWyDiCcna0wDqfsBgXk7Q0vK9piicnVJPF3CBNgBhzOHtQPcUWbkxxKvpV7qxeH,LmObZ3ln76BzTAXLH7UdQSdwEn1ufLkmTWIDOzwIedpFp8NxJZd0gRb1fiBCeDTr0PTIa5SzLlb31VvsoxAf379AA4jsApU8rZAknAHwx2jpH0i3sdtCFAKnpWYVeI2aN6DG8ljzVWODVBObmRUNafaPVkclIct5Sjx8rV4tYoyqHtpEwLxJ2NMvAFugygJDpUk6Ar9JxHyw7SEAcfDw52UwpX0RS1GH5OGNFXyGVb4JCYUi4mlcabe0IDwtRCdQ,7xB2u4UgdwbHgMrAjppfDVtBS4xKdWtr8ycW40UgkhJgaMxEy3pP10NOZ2WzmIzk3hXLnRIwCryw5d1MsUpI6c9YVzGvzLMBnPRNGBYxczai3vAUDfntnPGy3gQj2aUgXru3SLoqcRZIpmWRiY0jIpPf9ZhHnciWi4Bu7ulC058inNbBDllrNjrFgcG1U6y0Hd1oN7XAz1W7w2N9NJoMvwUSPsZhZQXpWiPVyJJbSrrCD99WvOCCSEHcI84ZWL7C,05b1ecMLzYHU8VR0j7snr1W9guKg7B4sLnZKw7mySaInmbiZeY5gc2X41uDuOg5J5bkHrWMVorD0fVBDbSNmqNs3fe2ZFE7kqSNT3dUwlGMtRwJE3sxnTFlb9S32suiRXZeOPXaClqdShuBGIeDeHBenAcmp2zEFlrDTQgZzxtzvEuKrCI8eEVkPSPUv6xVWI9R35UEz6lDcBnpqJlfK1BWuvpP5GLcbL78bmaVQcX6s3oCDVu39eIJqtsoOuiM5,LUBDiw5HSp9Udaa43pOzTf8hVcbrhz2CWuvydg3WNUw5VJjPPlSRUyvmCZnJNaAIKR7qaXZUJUVfMbKaljbLxYaHJOvnItTxqk0BK4sxkFuhhEnd7FEF6SQSfjF0XBdhTNKLqymU9O9I7Z6644jNDnZSB2tkyJdmCY3XhCBPXQZzoVEWE8SlBzbvWf549caO45K9gXOdjBYCuCRhSZu0kIQTbUUHa4K3uUetSfzbZ3GsxM9Nh5ZyD0w5obBXitxd,oiDPl0OsZvNpK8EkFNZzRTJis4ULJ0y3fUyWGICPnwuhA6CdgLYfp2dTyZB2l65L3LzMqUNUwBvUHl94SnNGQiRgsZ6topG0aFDMYu1DQFNEqSGThZhTqLJboZQ0gIV54tbSQFOnAmaUMXOIoaarwmYjtIhHSEE6N6MFSzCggRpU03lxU7nYOenBIqcL7oXakQlk8UmLCScIadCygsJSWttI1blabgY4E1RxGmEVEmCmhDbmZ4zOngKrAMBjL0bF,y54tB80hF6ElFuAMkTsmgBe1qJbIbLtgn1qEZOCBYrKSKBW8EzzCzELbM8Bc0S0UU8XDn5xk87cSpa9ShFTbSmwWSyfyVDVXc2JQD8NYdSgZaDuECVnWqVL7OfgBafFqWUPvW5ko8XaVzy1xVrG7QPW22LFR2iwlJCdhW77J3F6E3E51pvWB0gXhWn7yY3gWp6gUZE1eUKS50Arv44tOkdvAZKATF3bJoylvbNRkFtVoXuhB7IWJHExNPVkvX4qq,caXKLjh8zcsQq8q05d9aP9YxzxspaifZrv5Rm8eqqDmRrZkRJFPVsWjwfOZEv99EsMu5NTWVI1fa7gsWmRB9mfhZ1kUnJ3AGCdqKXJEKIgmfSIkkF6QxhQK2U0HzxVG5Z7ySo1a1Qwpj5dWGv0IFwSrcAoS4oflu2Xzf1X4t9rV9hadKUg29lVQuxN2KjRy1gtZJHAjUIMjRSkupvcbBHnUIE8tDPAzWIxognzJEhDCD5rGOvqMJ6vXjcYgHw5rD,VE7ojlstglXH8yVb0J9eAudXOwCnWOb7SWVhNJgpYaTm4eCE7LWIc4uDsLFWGxEYftDFnlUD3rUKTG55WT95ft3ItResFIeh4Va90zZmtMRzV9x2VyvWktUC2nNMB1dPoPpJa9bqXVsKMYvFkv4q6DTuyohFYQccoawQLWEej6W3K6tB9OofkssuwsKjCZYDP7GeJswEez6g4gJdlZl3UpV9bnPbF46QqvU0XuzCCgrC46JPvh8ScMomSL5j1tGF,XWLu50pURNyVbLWSbtrQQe0m5pOza0sDQqXxMJE6KnQVTxZvxtVBLOq8W8gi3S7MDQ3MLOH0nW4l5ugmIpsC05l4WFtVGZu9ZNGcSr1AAwM52GIsBjO5oaSpSfJdagDjhCm9UUwidEhe7Xkmu5IYKGyQYZK9VcBUfOR5G4XoQ1VpajHMDapnZYuNFyz7f9WzUNLI5Qbtv4sVl4pbGEqOeznofATJCN0br8yM2BeWaldxAIJASHZebD6fzyWIzYJ1,E49ZbU0IAh50liWnUk2n9UzczOouYK9Dmzypm6DNVVTN8V9p7RCwIRPxBej4USP4GBqBZsOLRn3Xyr2y3gMC3PaD1PCUD9vhDAEyhC7R0FgXPhnPkdHCngD2GdTZrurqZwBiCL9NUUADzlGlKgWZWGNmGaoWrU20b5jV8O84JLtLXv3Zv7bOOrVwlkNWtgG9KAQqI64ppIWrFSX1BYv9ylwieKRRLE7TrjKGi7xlyRBnRs76sboCWBCCjuvOvqKk,S5VHra8hXSaGNhwAcnypV8oLLIYKzj8ei6lk4LiLM2YZTWVRJ3HNetcuuON25QIEUDf8t4eaayEt9xJWQY8kwa9JlITAerEO3cweZTOXUyKCQWXin1512pgJVWGyLmVJVizpIJ8ueP7rtwH0QrgeE6hMlPoycms45VGidwjrqcGV1CSZujNyBr8cj3BPjOt6UcWECVylXIxWxyIHN6HXLroMSbfmwKENrMknksiGVRG5S24RxwSxMrYF7mDOlYYT,LoDxP3q4KAmB7dErWcEpsBt0CBDvbDPLfFH2p0C2UKGg00hqJaHFeC9Af6wETQs4PDVl9jWlIxI7BDI7kwRYgI66NrDDqDb62FMWBFTppxlUbM6YbrtdykCfa27ZwFg8wzYoAfAakPmXGkSoYWyqjPxSj8tJPSu1eRvSTsj7dN75m4tyVeUWocRgioPB3FzHioZBLnsDMZPA2Fkv7PWLxf4fDtyaUp1dOPvU4AttkefihLFF6jqiFEYUcKY73GqD,r0xrhSsKsgcRSONO6CcZ7CxJGd0jIbxYSIE9y1pLQC05y6Fb81M3MXQit0J5KN1X3nTevcQv4bC7IPkd1MCQAiFuhvQXv0euzQJMVzh4Ks8yeTY3NbudXSZq4JJCDvoTvnaaGFzE9y7ZWwdslVm8ehQEupbObyL5dKYYbdDZkt9mApMGdglGHQM7u2TfjfniNiEb9oJJhnmNjaXqXPwSNyzwKeMIOsxW0pKtDU68Q6QKY83ffJxAiqyndv0bT65x,EIpEOYR5ZRQ5AVq5DRYrYuG2n0fn0NpJ8HJydKEk2Ei5cyt2LC2DnkISURau3Mp5iauglwfldZMmqUFSc3OoZZj6HlyyeJzQaRGm0bsjTP8llPYZ0IXFMORqg9BE1DNftTtSRXmTeC3HL6GiBjgXgFzwzsWFZQJLw5qQOvZ9R1fR8NfVRKJAUHTMRQEBuVL8OyKXoeK7iv5Rk4U1gZaSiqVZjwAu1OD8xgm2lXWPCXWUeh7Qk9RbrKgyNTs4s4Er,yVkOM6WcpeaNSsLRZrATCwkZZ8auJ7PA025HfGq0Z9MqVQS5FHwCujq8QSFgCemtdaqmQeR1rAv8Fa5g9DoVvzRX7LnYbut0ge1amIOmzksFRjogZaZRaypQJ9IcUSI5Uqe4Zj8Ll246eonLQs7T2FemooyKqaCjrtNX8VJFzRx1jvQLhUBAs551UCyKp34Y8DN0iCaeKR0Xudv2bF2JH3xsNV5ogSZczeMFQm3ZAPqWu2DhOvlJzgUM37LGJOnD,NRfQYTsgIBCqRqd6ZPvYhMkt2JWWu766WWm11XKV2e4JVefzcX4w5GFyfnGwO6SkAjX10oYt3gsZvv18eLfBaXuHDgCA7yglJzDk2zvGlFG1gnOmQu6upFVEnkKRp13FWnemWLhCeWLnbylzYvHkNOmEsneWbrboP4cUHnep4XXcu19J8JhYAg8xuCgxbIk3etaNoGVql1CiKo9oNFG5cuDFT0qhYwyEcs2pci1qOquGiLvsBZqAj9vzs1zr8Irt,InUxaqJV1SAE7ogefb5ycgtMXJFAWbBMD3Lgfa8Eh8Jfigs32jdZaZJl1SdRzvudqA63Vbbek7vRtGjAynJQcFvBcBnXIP3o88dJ2yfQvnwSFcYfz7Vg884JaF7EYtJkUNZYRjN8lj8krEOz9KphfacApnImfZPuIHZ73oERJw96NdUECgnPv17nN9hOHXoaVf6g3DwFCwPqxRFgXFNPKCkm4nIs6MjWHIwKtDEMooW9xyAAXIkyveSjZZ4QNd23,p6uenglPrUEJpQ1hvE2SZS2g8kt9hTWBlAuKqhQ2IvYm2T1ZnEDWpXQUdyvnUJ6djlLOmSBy7bLKnozVaF1ycvCCJBXZjzkXIIErC97nLckYYV5C6hffThwjteXH0lYtuWfJNMvoSpZjIfoIpEGZ0v0q1oFFnhG3nHYjtj9T5Wvc3bqm7DMocVVE7yafWx4kf020YCj1tfPBGPCBL4sA99hKfA1K15I51CR5W9i10Me2OSJHr1lp9vQSsUxsrgQi,v14h77bKPgDQOn5yAbBBD1JCUp65kbCshVUU64rMqm5db7QlPHZxBZ4UFDx7M7l8rHfoH3hrmXQYbFBOOBY12si85M2DlC0n1E4lwYQXno3o6Zk38EMECmfgznehoASAoqno8v3PDBmxQTD11IGCbFh7SQ7p9UsJKId8KpCOlPC9W7yNv9JBe31LckuVZiArGZ6d9xsDc02iaEKH5clsMjbBMglMDmK2H8BGrov0bD0TlNI0j2a0HR4ykqyJZKkR,95wRXTLU4Tvrv8PuiYo8jyW9bbRnMKeS9LwLl79dJ9onQYGdpcHaLLKMsqe9cVbvWfwyEtExuV64dF7azwZv0kyszWPFzRGCWlbVFdQ4NDP9ghoYUwp1r7gT5gsdG273aUL7eHl59H2MDMyrdI4nO5EHsWl4K54t0CT38V4iooiDIfUZfnt7mhOXOgLwAji0YsqKFjLfhzaxexgrPkzOronHD1v0kbbbLkdGrp0TRZ2WBzMIym7U4gmsRawhhE2P,Kipbx8J9RMpvFJv8GkZOuCoaqC4VRrqFAhgYy8ObQySqohfZ2JjJwzD1OiYpuD3lQqLGF1xKcXJnacCqqzAjVQhrhiBVMhVGINSoH5BQe23lp1hQ0DhfBiXkM8enjE3jlY1mjetYBfQhzqN7YTMkOi3lJ88qCzMyhQShuPx8xvbZwFT75vgTI6EKrwYjCn17hZb7epsVFJN7JmbsxVVhO7gHw7vh8dwARaVGUJ8XXUN4xmEEO4j5cPg7gc0VV8A0,e1t97dSTf0x9Xt4KrtFXkKpTm2HELe4VuA0EdVTuks8yweQ9lfDUw2pVsVRJvBljHBwnnIDKpB7SdBDtXh10yMElH2erJCaCKvhRsA4kog37ZXwIfPW25JnCXmbFRoAc3XrE4ajrkzTq8kxI1G6CEGOrEwUOBrvlwj1jYQ8Tbx9M8uHZl2st9yNcRLGinX5nHHEgafhtcnIj2FgeFtFwu97yq7d8IIVYLrLCW6Wn7lxpPFgk0ZWr3RY4MFNo22hO,ZXQVOS1lWuPkwaZjICpChjcAsPPlqLEyrPOz1ynX0meZu35AKEfhIqPFsDRqJsZbUGwns3h9qktr3d6lGHjN4oV3byzY323v80QMU0nJkyzh30BBDTWMsn86VgL8xEnUNYvLSOv7UGPKv2L52WdnRpCmubTJLIzJuyylaz8AVLEQ8A5hzzSRijwtsGiNmJ569CCOdVLiiB0bvDBLw4IfyfVC27EwSQilfy1gcAsGv0INLQRwJmBpF2tzpJb9SRb2,Kl4cnTsRn6r9leox5EftjjNGlraZ69ZbAv2Elcq3xHn7FgByslihrC8uKV65KmThBlqL1Ec9EReaxxLqatHldhdWoQPtUKqrV8qczdjS66iSpyhhFdxa3DQ5ABriAjJgqybEW8y034uwJv30MzL2PHgY3qbPjfD9PVgxmsGo1QimYO2wC2SDSrD9gltdDPR3nSOCJQTZIEGaHfRKpnlSlV0qcNC6BCn7eARZurvmeWlkKHA3bf4FFyWHr1YzBskG,bmpbPRevTCUYvtEFPQi4I3YCFVV7qIXpmQG629tMK7jsJMVLCIoKD8NyVkmOXIfgxGSRSGuGgV46ElTK5RYW6UZbtoiSiBlri8IXqBgEBwQ70DTxeXw2DlGolx4WrnnpzCXULeiIQ7yF95jDUZdf9YW9qo9oWKF5x7KcedLZqlpegYNB4avTYhFksqx2JKeLNrhhFzNLtz4V6tNWwEqFjg0XrpaYPn4hrp04IYVi3WtPNWgnuVyOCLXqTNAkBNov,03qQJQppNpC7TyC5sFvpchWqYPR14RRt8jqyhBM8DNdqphYQ4yPc0ZAHawGn4zGwpPy3lwv48Xm1yqNFD7rkoCYHaMzsCEG4fPbhAFiicqXLzNEp9S9A5jmP1ZctJMS5Dg8zBvfh3zga7CQ2KH9RMGZQOKs3teTbVhMxugHlcprcQhNrCjb8Pd0dtPMENXiBKNKiPrfMjJzcBkWwSiAsCg11j4rXfzMpcznSzW5e8goPAFbIVbmbxVRBiKYAyN5G,RY61CPMZBPZsi2kf34QcOqhZh3v7HXgmYONfpx3mXvSKSgJ5LTp8UQk2dUjnWn1qYVk6KtM1sInXzqI55KEG65XjERN7X8raZvHy2fsYkNatSTsFTqsDWOzsl1tB1Aj6kUEOwlPTQxWerHkssYdvNEzcqzU3mzvHF9IrUw45bM2lZFldJBoCcuBERKj7mpiht2vxeNpFoHbZtJ23oo69IXbdAVATfkP5KCMTEWHuWZc52AsSAhO6YTTgRD3LxWAY,vJSV556VrzpvvrzTJrQrlq1lTxnCFYyHOHnlaGpx9khSfgUptSoxhy31oQTek5zk5f7G4dKMlhShs1BpBRiZd4laTdazsRCKlNOeJITUf2y9ML3T4MEvlPyShY2hKDSLobrXd7EZiUY6vLv4VkbptCApiVWGLmAQ9WgYwHreDcWLW6NJldtt9hGZvtfcefHAE59bRLIwFIYRIdjTnAxKWg28qTFCTxlVw5I4uW8Or54zV4Rh449RNrlGP57C1Ovu,Vl5hezDGWA70oe18oAd5qSrAZdXPiYwi05MkqYoppdE7lazkJM556oLfupKK0P5mR2jEGSH9XMM2nLRB3BAyVp3j0MtWfdTQGvzuOCNWoAjOZ30fHfxavL9dWsZvrvzBTWevf6K1AHtH3DvaJ3Cq9WjUW1L0m3tKhkmsSvmygdzQboCjrgehe0grjnJ9S4yMNTbU9ccJUP9ILLBdbt28OG3CgKxcROrhV6f1y10IV58Cp6s4GNGOnuHsBi1C7w11,t885cRd3KGoWjOplbKwA0HaSLqdXwUmfIb3qMazZr6vuiPip4ToPMrYeBwbkjG5GO4ARvb2EcOUAb7xLgAvhkWWHA0vYcPM5yP5aRahYiRne81rDYNSwzi8AGxlQnw7PofH3LqFOm9Ymc9DPbZXy8R3meVXM4Q7f5K1WMip1A3Fh1R1s3D6gXYzCspxBL4jAUuBWmDCKdj9vGU5OxrGOQpuJsphocNCXBAbpeg1atoH0a5bMum3zKQjvUeu8WH7a,q9Sd3gJCisYWyXp9LvAz9ZYPgG0KAZgsikloN5s2PZdYOxqpDS70MZgjYeyUhEk2H3kkorjArKCvODKxJo4r1Sp50HGgJ6xw7ucnoqxUjGixoZ6Ff6NCuti8HKKJuVYjko1WT0EcUcR2qGypYpse6Y4ziwjp7OHh4cggGK0LbZuDZrgU0oYMFqonzbCTLcKux3qaXeuxrd0i64lvBTBq9CxnUxarBA8a3WdxJkYMIMVy1BEHYeEl7I1tfyOUCMRf,hb9AE4ZaqvzIxk6YPnVvh5bEOKGwKVjuct03BKXMK404XVxGA14ChyTWyEYkQWDLmPnjvXo6bJT0kd5l5rwgOfmCqBIk8DCPIr3gtWeXTvIBd7TIbR2YZbLI83PpQb3U5mAAz65Lfr4ypJMLueh1fejlICx1m8dFP642nnmMRE5DCFH4OsIYN1N5svPw6UrBUnBp2ZWlbcu4GCDtB0jonY4dyVr4In60dz6eM23lEwmTI6ArPYJgHA1I3ivyvnPw,4SU6kt4Ur9ZAOr0S15LPdFLaHoOBhUPBekAzxa8JQTlDzip1cvgBtpLMF771kYOlvBZKCbKUBM8shHJfAgjsDFNIUcEf2qeLn1nNA5eGQObX5GtHhTiqO2KDED58bylVRkO6Mt49ULBKFxXqfbJxWoUl0uAD8j7trqRLeLXMP53MK64otIvBYhCtGKFLkVZzdOB3mYBwlXfLVPCa8sophz6FRwG1IfjN78YXqQcUJljDfMttsIR834FqxoCLR7KY,a6XgdajUq5klso8Ju3wz7swrN2zU6TJcvwE6hHVezq1DZojahvqLgf3jDgfmvoklpsJQuPK8aeC2lTnyOOKDI86EOVZxzAanRvwbj2VCP2Q10N3CXY2kq1ocTA1huRWmSSdb5HvikVHR3p3MDzI6AaAR26dpH72PoENvUKgFCSac1nmKfJO4RGNB0jn5Gh7d00EyhRCTUSb7cPxpG4BFHRU7XluDIT1wgdbVxKnccoh9lWh2GcTPdcG1SEDXTayq,WNY3ABU5FnqQ55hvPK3bkAfenCSCG2Vcf3QgGIleqS4lZgahfp550Y82xsUqVPE8gQCX8fOwr332BW8PdNelCRxNmU4hXZ76O2xYpSpVv5oJB6e5EGj2PMzrYEVKV7o2Kutszir9r5WnI4x6Hc7mdPBMH2HB7AmpaR6tKc67Px3oQvaomvIMIPPqLNgWKxPm30JpAws1hbbWdyeH8SAkdn7lsf81m9TnQRjf63MGCGkwj1QeV9x1Xx3YrFSjaB59,wQPUrYObDam9KSP4rgN7wRmsRy0YaxC6y5CIL1PV27EfXiayIJZ1dRCBnRXMfwQF4117fntvVHSOJFLq8n6UDJlNm3Q3e7iL2aDT7WdQP7UhXBhD27D8MIYKqqzxETctJUdPsWfAwXClXZ7UCHIoKC5rWXmkNI2UKaLf8HTf2wXkl0YQUnADEsLvbhUDd6EODTZ3xrZrunel7lADbYENpkA1Ztu8XWKm5tm5c60oaYkW3UWJ5X8V5GGLzTE5Lpkr,5pGTZZW3wAZpMltqkAw4GrRJ4qgabz2434hu3FTZsm6XIc7Ze2w2WBBTU6PJLP3ywUJ7l2VsZTDKx10IWylejz0lksfvFnxfAH1meoZvkQpch9tjis81wLFXBOAWwN2CXTW1NKYquCTcPQfkGUKAqfTobFtunZTj5h1l7QiNaYigAKRN3b38BeAeGYuuJaNZ9vpSpbk3TO09ASD3v3JoAb3lnCzSF5w6Eafie8IyrE7Hk9g1ayrnN8ojEnv7ONdR,CgcLL7r6kdeiKJ4sh8K2AB9aPEckiBTThqXRpBCN8CFQxuo6J1NJ5byKuRbSDFxBQwoH4p66EDNS4ijnt9sCXp1rX4mfNxMSQ8o6k1rjWJAbue3cXtDPTsQOtrTEGboWDDoJHwJzKGwxgaS8xceDg5rkvQDQfn9XFXUYjvDMxo7gyaIaREQuP65CcbOmBPBQ11Chi7DYnqFCFnhTaqzFP3uf8RK9BaP4nesWxQHLaFfB1ilD4H1maZrCi15CbSYJ,a9M5TLYusKDTC8tfOt0dMp3FrGYNJjMBRjq490lWmp1eoboGMsMjlFJa2JHlTH1aWlm8AMeyxFdT9tF2do8Q8BcAgpe15AI41by2UY9QYaBI6f3gzAqv5lnIsQvVOGvQy5De908cg4Zglht7H70cfNybVve6bgIrpZWp8GMyVQkO0UaM1r5xpJcbBwURBNIbBuFkhO5slePHjqrGq7PexBnJdZHOdpfE9Qc6Gk8NRn7WXyG4WInRWan3LQ7CnK0Q,2B5UVKeEfEj7pHyFy5tlMbbvYf4Dbcu7ZeDBOaERKTdnzEL4xXwtG6iSNf1688704lCecjTVVvRaz20nX0ABWrNQHtjisRogqiT3Pjxn9e5ERN2p7RHrKHFErZSFADkuatXkqY7cx3UzRS6Xp2R7v6o2JlZiSaJgowKARwj5L4VFF3fN1bLINXxuMRrTEX1kTnSOisv0TeVeQfAuH9FpGWqHwunb6zLWgwPCbT6eQvHwj1WPCrl29O2Vok03umWK,U0vqjkjosApShzH87gYkwkA7Pwk2jIi5MGv2rS8ngzYinfkzoAUX8w5x8lBVm5EYUMCvUkuSskgHk2sAHwrkBq9px9pog9JUMhzOt4sQ9cReigAphLc1XjqEtz0Rz3KZakvsDbpWjBjlp8k4MpaynvqqNFKk6QWXkDqpKs7FQx2GwO3nS5HfVfPv0n5KvMNdOi2nrIfoUSDOCwBSlehH2e2bVmAkD1pNw31uCFTlfqtkqhlULt4hIzxGAc8v6CNY,TcV9W9EG3c3chB6iLFwvWxuNzvxPKaQy8ccZ2eWEKZWHrU7r29zHIClFTRGbKpKG5YEGaDG4apdTc4ZzsWvaF3Qdv05DcAjwZ7gX79OmB0qv7xzyfenkuMbK4gVSblRkOFPInomKzzdPCBwbWeGMTJ0jqlqpOnJO0IwiR3HILo56DegGUjoRzyflpE4KcS20HvX3X9bMd6Urb5EgEgiXtPqICwYHXY2itW9f9iabFZMuiCcwG7T0zuz2F9n7IlVJ,CsYTChQDMmZbbNBjKhsJ6ibvZqNeMzLYExTp3NCyXNJr3dgGukobL79knTLuUVb0Lrkr2gwVWHTFLDeei9vcrbycMCUhb8P2AmLw5MrtpqAd71My0Uz10pDFgeKia3RZJuh7A6l6GmrgrhL9pVzSlMy6sTkXHyAM3Q3SkTARp32L95Qvd1KokprUt2Pi0GW1M9FpBOa92IsXFsgDJfYs5DUlnEa6zeFRoUv9wXAFgwKCk0q0gX5Xk8sCHfwBfXQ9,7xUSDuwaAHK409DvxNAlYecgZ6qFuop9gVYHfu0yDgsax98aWliHx9OXkSDl1QY6jOrUe9uWG0wHKHmOWBGiLOda1mTthM4QNbM1mnOuKUdRlsueKNi8Soo6QyEqBrCUuzAnOqInciBMRl9POLU13U8VOIjDKEMFJQHJdH7JgoUXEakKOjJxCpB59ccZPxJsPEPwGkLMS2GboUJSEyU7N018oD3YciG9txmwv82E8IgdNw1mNzz5lDNg4Cj9GXWV,Ltzju8719W0rV4bFfM6ib3Xyk1mZVmMRfOfJ7oZiBDzFiAp9CAZ4uyf6OI9qmkRysnt8d0BxUHj7hlPnYizvk8K4Wir1nZBh7lEj3dmAK2CQpYL8jnYi647xVO416GMXe53xwWeTpMrSFpzfqwIeyvR6342SEBKV1nMS4mO1I1oOygcNRopMI8Ly7IyismnnK6EYd74NWUpwRi25pjEe6XK2ekJBpGlev0aj04mFutUzqpRdDKtKG4Zvxu9jMHOj,JeqLrxdJgZWGqB6eKoq1yPfqLLeg9ZWO0VhwBfpXMgR7GUuCbBd1L3Nt6vKclF0SLuJe9omNo1AzlLqIBsAbeC7L9a586uLRR7oHdnUraWLnaicETnog5Xr0OKRmpVgUiOTDNmkyeD2Jl7BYTH8v2oz7dzqBGnDKVE7VplDR8pGfyUE4UTcoyZrIh8XexOf3GK8nbTrkuCio3G3yqSpt9n0QUzhNN1XnUYSdXHOF1WEZi1B85GiItKLugEvtVQfp,NYXBkYc7aKoN5NjvkQ3SJzi7HU5hd3IUUUlSNtXREaZFkK2GI40282cPJClFYNrk5ltVu1UIzNF4xLQlJsy6j2hUewi6L46vAyN4ztQufwp493gfXYAPFFhx3VuqZSs9JpJGp2Rp5bF8rWYIOCQfnjiUWpZ92IhJqYFJD9SzwaoydF72Ia9kuPs0e0PkrtB0c18GFxhmw4UuRGKe7K8siSdLCRlsbNCqf6mTLMqRK3155yxnn24HEKeMVJKeU8ln,jKg7ApmFsGWp2vfmdkMOIWRwGqlAdsV2m2mCddYu8Zv0mvXATwyVtv92liPUVSsBXOD0tGPDOSgGuHFNFUt56ZSewPjPJUm4tEendbIODFJPvGOgOjgWesRuezVvYSHBJ7yqlmRYnoeZbGHQMVdmCEVGhqP9OFdabvYvEuwRzhff9geEXJUbeGXvClylVFUCuxosJCYFFXQG4rhmXvSmCm8iZZYo9yRHxk9Z6GUOsfQWXbqsfi3zkUOfGohulwKZ,rjuKM6bKR40OkSbsE9aMXydaGQwD0H1DoSWhz0qXHPrUQEWMSUGMse8ymYaKBaJgAFIckaQDv1DLNj6YQQu8gi8UXf9LXLxHCtRGRKNe9AWEXTajhhFOZoc03DCzsE2vvUhdri5rZXsUi7WVjGsZnoGKoVuwzsZjBRDbxR3d45NACy9Y5zztySLMpqi0umuHOgAxS2muitNWBv484o2gBPFlXfNzJaBrn0DYAMN10EP3chi4ZsGGSF55GchdUCxc,KKT4oDo0uj9ZNwUBOilHK9sB7vCOpw0v98Er9cLoLqWSXWBpXIRhOkCR0UzagPJ4JlriqDUskY8zOJ'
2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [2, 5, 8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cli,ent disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [2, 5, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server received (12714 bytes):'
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server received (3670 bytes):'
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:9 [2, 5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF
2017-07-13 08:33:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:33:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:33:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49794
[ThaliCore] Session.disconnect() peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] TCPListener.socketDid,Disconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
,# setup
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:153DC3B8-63CF-4A5A-8EE8-E019C23F5C8C
,[ThaliCore] Browser.startListening
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 08:33:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 08:33:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08B6D133-C3D4-4338-B019-A18C4389675A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", generation: 0)
2017-07-13 08:33:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"08B6D133-C3D4-4338-B019-A18C4389675A","generation":0}'
2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 08B6D133-C3D4-4338-B019-A18C4389675A, (syncValue: WOwVT1PzPrvbpdcLcNwH6C38R2A2SBNR)'
2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:08B6D133-C3D4-4338-B019-A18C4389675A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A385ACA9-6BE4-4961-9C6A-7F8665F19C7C","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4804A3A0-BF11-4E49-9818-17B476E274EF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4804A3A0-BF11-4E49-9818-17B476E274EF", generation: 0)
,2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C8344525-57A7-4C58-8528-26E881A5D49E","generation":0}'
,2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4804A3A0-BF11-4E49-9818-17B476E274EF","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:08B6D133-C3D4-4338-B019-A18C4389675A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", generation: 0)
[ThaliCore] Session.disconnect() peer:08B6D133-C3D4-4338-B019-A18C4389675A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:08B6D133-C3D4-4338-B019-A18C4389675A:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:08B6D133-C3D4-4338-B019-A18C4389675A:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", genera,tion: 0)
,2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WOwVT1PzPrvbpdcLcNwH6C38R2A2SBNR","error":"Connection could not be established","portNumber":null}'
,2017-07-13 08:33:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WOwVT1PzPrvbpdcLcNwH6C38R2A2SBNR', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"08B6D133-C3D4-4338-B019-A18C4389675A","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"08B6D133-C3D4-4338-B019-A18C4389675A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:27 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 08:33:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C8344525-57A7-4C58-8528-26E881A5D49E (syncValue: PUnS9BqqW7cjgFEiKcpUvq48SULMZFQe)'
,2017-07-13 08:33:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1D68BB73-BB6B-477C-879F-EB909ABD2B12
[ThaliCore] Advertiser: session connected Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1D68BB73-BB6B-477C-879F-EB909ABD2B12 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49808
,2017-07-13 08:33:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PUnS9BqqW7cjgFEiKcpUvq48SULMZFQe","error":null,"portNumber":49808}'
,2017-07-13 08:33:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PUnS9BqqW7cjgFEiKcpUvq48SULMZFQe', error: 'null', listeningPort: '49808''
,Connecting to the localhost:49808
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [2, 5, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49808
,2017-07-13 08:33:30 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 08:33:30 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1D68BB73-BB6B-477C-879F-EB909ABD2B12
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D68BB73-BB6B-477C-879F-EB909ABD2B12 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1D68BB73-BB6B-477C-879F-EB909ABD2B12
[ThaliCore] Session.startOutputStream(with:) peer:1D68BB73-BB6B-477C-879F-EB909ABD2B12
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,1 [2, 5, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeS,treams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [2, 5, 10]
,2017-07-13 08:33:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:33:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D68BB73-BB6B-477C-879F-EB909ABD2B12 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1D68BB73-BB6B-477C-879F-EB909ABD2B12
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:1D68BB73-BB6B-477C-879F-EB909ABD2B12
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:C8344525-57A7-4C58-8528-26E881A5D49E
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49808
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,# setup
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8E9FDB0B-BCBB-402F-846A-DB533AA0231C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8E9FDB0B-BCBB-402F-846A-DB533AA0231C
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A238DAC4-F410-488E-BDDF-B0C8DE16D905
,[ThaliCore] Browser.startListening
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C8344525-57A7-4C58-8528-26E881A5D49E","generation":0}'
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C8344525-57A7-4C58-8528-26E881A5D49E (syncValue: E23jfRn0yf8SPbu0QWdqj5MQRuiM9Q3y)'
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
2017-07-13 08:33:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
2017-07-13 08:33:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ADF8C929-C7FF-40EC-A17B-BF06E75C0D00","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E9FDB0B-BCBB-402F-846A-DB533AA0231C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E9FDB0B-BCBB-402F-846A-DB533AA0231C", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,[ThaliCore] Session.disconnect() peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", genera,tion: 0)
2017-07-13 08:33:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"E23jfRn0yf8SPbu0QWdqj5MQRuiM9Q3y","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:33:39 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'E23jfRn0yf8SPbu0QWdqj5MQRuiM9Q3y', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:33:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"C8344525-57A7-4C58-8528-26E881A5D49E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13, 08:33:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C8344525-57A7-4C58-8528-26E881A5D49E","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:39 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:39 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:33:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F2F1D66-84E2-471B-A46C-8EF9A1C2271F (syncValue: h35mCen,bEixgQ0Kc2u4uVaG8kA2PcUrK)'
2017-07-13 08:33:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271,F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49818
,2017-07-13 08:33:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"h35mCenbEixgQ0Kc2u4uVaG8kA2PcUrK","error":null,"portNumber":49818}'
,2017-07-13 08:33:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'h35mCenbEixgQ0Kc2u4uVaG8kA2PcUrK', error: 'null', listeningPort: '49818''
,Connecting to the localhost:49818
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
,Connected to the localhost:49818
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [2, 5, 10, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 124 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [2, 5, 10]
,2017-07-13 08:33:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:33:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:33:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:33:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 08:33:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingA,ctive":false}'
,2017-07-13 08:33:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49818
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
,# setup
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DD83DAC8-0C26-4E49-AAE9-3B514AF29B66
,[ThaliCore] Browser.startListening
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 08:33:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FE67C612-B683-44B5-99A0-83F49848650A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FE67C612-B683-44B5-99A0-83F49848650A
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 08:33:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:33:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}]'
,2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}'
2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Filt,ered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ADF8C929-C7FF-40EC-A17B-BF06E75C0D00","generation":0}]'
,2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ADF8C929-C7FF-40EC-A17B-BF06E75C0D00","generation":0}'
,2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE67C612-B683-44B5-99A0-83F49848650A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE67C612-B683-44B5-99A0-83F49848650A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:691646B5-B1DE-43A2-BC53-4028E7B0F72C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "691646B5-B1DE-43A2-BC53-4028E7B0F72C", generation: 0)
2017-07-13 08:33:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"691646B5-B1DE-43A2-BC53-4028E7B0F72C","generation":0}]'
,2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"691646B5-B1DE-43A2-BC53-4028E7B0F72C","generation":0}'
,2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
2017-07-13 08:33:49 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"ADF8C929-C7FF-40EC-A17B-BF06E75C0D00","generation":0}]'
2017-07-13 08:33:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"ADF8C929-C7FF-40EC-A17B-BF06E75C0D00","generation":0}'
2017-07-13 08:33:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 ,08:33:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-13 08:33:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:50 - INFO thaliMobile: 'Filtered out discoveryA,dvertisingStateUpdate (was in stopped state).'
,ok 130 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-13 08:33:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-13 08:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:73407B78-177B-4451-B1CF-EBBD294BAAD7
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "89411800-5F3E-4FC5-8746-3EE0393120D3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:89411800-5F3E-4FC5-8746-3EE0393120D3
ok 135 discoveryActive should be false
ok 136 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,ok 137 discoveryActive should be false
ok 138 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
ok 139 discoveryActive should be false
ok 140 advertisingActive should be true
ok 141 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 142 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 143 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-13 08:33:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-13 08:33:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 146 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-13 08:33:52 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-13 08:33:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-13 08:33:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-13 08:33:55 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 154 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:ed6a15f2-0685-456d-b995-682649ca35c6 error: startListeningNotActive
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jMDgPZRPO4aFmoDcDof2varWbJItO8iL","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 157 Should only get called after multiConnect returned
,ok 158 SyncValue matches
,ok 159 Got right error
,ok 160 listeningPort is null
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ed6a15f2-0685-456d-b995-682649ca35c6","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ed6a15f2-0685-456d-b995-682649ca35c6","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 161 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 162 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D3EBCA27-99DF-43F3-8725-2C5B3A422849
,[ThaliCore] Browser.startListening
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
ok 163 No error on starting
,ok 164 Got null as expected
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9TTTa4enQcWEQlc12ApwOUtSdTJpaUeS","error":"Illegal peerID","portNumber":null}'
,ok 165 Should only get called after multiConnect returned
,ok 166 SyncValue matches
,ok 167 Got right error
,ok 168 listeningPort is null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:691646B5-B1DE-43A2-BC53-4028E7B0F72C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "691646B5-B1DE-43A2-BC53-4028E7B0F72C", generation: 0)
,# teardown
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}]'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"691646B5-B1DE-43A2-BC53-4028E7B0F72C","generation":0}]'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"691646B5-B1DE-43A2-BC53-4028E7B0F72C","generation":0}'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 169 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# multiConnect properly fails on legal but non-existent peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DFB62186-974D-4441-A275-25334EFF0AA0
,[ThaliCore] Browser.startListening
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 No error on starting
,ok 172 Got null as expected
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"swGn3qbmwm2HrhOnTa2amjZFSV1CztFj","error":"Peer is unavailable","portNumber":null}'
,ok 173 Should only get called after multiConnect returned
,ok 174 SyncValue matches
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
not ok 175 Got right error
 , ---
    operator: equal
    expected: 'Connection could not be established'
    actual:   'Peer is unavailable'
,  ...
ok 176 listeningPort is null
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ad635162-3ada-430d-bfc8-cab4dc0b82ef","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ad635162-3ada-430d-bfc8-cab4dc0b82ef","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:56 - DEBUG thaliMobile,NativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:56 - ERROR CoordinatedClient: 'test failed, name: 'multiConnect properly fails on legal but non-existent peerID''
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - multiConnect properly fails on legal but non-existent peerID, error: 'Error: test failed, name: 'multiConnect properly fails on legal but non-existent peerID'', stack: 'Coordina,tedClient.prototype._processEvent/</</endHandler/<@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:463:22
tryCatcher@/private/var/containers/Bundle/Application/8346F6B8-D9B6,-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jx,core/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:56,7:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromi,ses@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
,2017-07-13 08:33:56 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,# teardown
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}]'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:56 - DEBUG CoordinatedClient: 'all tests completed'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:691646B5-B1DE-43A2-BC53-4028E7B0F72C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "691646B5-B1DE-43A2-BC53-4028E7B0F72C", generation: 0)
2017-07-13 08:33:57 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"691646B5-B1DE-43A2-BC53-4028E7B0F72C","generation":0}]'
2017-07-13 08:33:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"691646B5-B1DE-43A2-BC53-4028E7B0F72C","generation":0}'
2017-07-13 08:33:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
2017-07-13 08:34:05 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}]'
2017-07-13 08:34:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}'
2017-07-13 08:34:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:691646B5-B1DE-43A2-BC53-4028E7B0F72C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "691646B5-B1DE-43A2-BC53-4028E7B0F72C", generation: 0)
2017-07-13 08:34:10 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"691646B5-B1DE-43A2-BC53-4028E7B0F72C","generation":0}]'
2017-07-13 08:34:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"691646B5-B1DE-43A2-BC53-4028E7B0F72C","generation":0}'
2017-07-13 08:34:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:36:41 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-13 08:36:42 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-13 08:36:42 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Error: run failed, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID', sent data: ',[{"uuid":"d07274b3-2294-4f2e-9b38-e14869561fb8"},{"uuid":"2e4e2245-ee90-4904-94d9-3bf7348c53ea"},{"uuid":"d3c978f2-16c2-4405-ac70-2305e0d7fe9b"}]', received data: '{"success":false}'', stack: 'CoordinatedClient.prototype._customError@/private/var/container,s/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules,/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/,containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/ww,w/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/8346F6B8-D9B6-4E51-B6C7-DCA36F7B84E2/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-13 08:36:42 - DEBU,G CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
