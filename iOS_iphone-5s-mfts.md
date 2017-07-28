#### Test 11335185130e646f_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/D119777C-DA1F-4355-B023-816B5CC6CD31/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/D119777C-DA1F-4355-B023-816B5CC6CD31/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53126"
,(lldb)     command script import "/tmp/D119777C-DA1F-4355-B023-816B5CC6CD31/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,2017-07-28 10:22:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:22:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:22:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:22:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:22:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:22:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:22:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8D15D785-6A2F-4E7E-9A21-13FA8385FBC2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8D15D785-6A2F-4E7E-9A21-13FA8385FBC2
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0DDF7401-312D-485E-9491-,18C0B9AD4278
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8540B9A4-3D54-4BF8-ADB3-A48D6F9E07F2
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1A3CBB15-CBE5-42C2-99DB-E96146346B33", generation: 0)
[Tha,liCore] Advertiser.startAdvertising with peerID:1A3CBB15-CBE5-42C2-99DB-E96146346B33
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A3CBB15-CBE5-42C2-99DB-E96146346B33:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A3CBB15-CBE5-42C2-99DB-E96146346B33", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-28 10:22:56 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.988317966461182
,2017-07-28 10:22:56 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-07-28 10:22:56 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1A3CBB15-CBE5-42C2-99DB-E96146346B33:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1A3CBB15-CBE5-42C2-99DB-E96146346B33", generation: 0)
,2017-07-28 10:22:59 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-28 10:22:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-28 10:22:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-28 10:23:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-28 10:23:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-28 10:23:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-28 10:23:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-28 10:23:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-28 10:23:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-28 10:23:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-28 10:23:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-28 10:23:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-28 10:23:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-28 10:23:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-28 10:23:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-28 10:23:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-28 10:23:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-28 10:23:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-28 10:23:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-28 10:23:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-28 10:23:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-28 10:23:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-28 10:23:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-28 10:23:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-28 10:23:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-28 10:23:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-28 10:23:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-28 10:23:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-28 10:23:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-28 10:23:04 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-28 10:23:04 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-28 10:23:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:23:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:23:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:23:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4,DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:23:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:50 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-28 10:23:50 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-28 10:23:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-28 10:23:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-28 10:23:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-28 10:23:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-28 10:23:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-28 10:23:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-28 10:23:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-28 10:24:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-28 10:24:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-28 10:24:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-28 10:24:13 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-28 10:24:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-28 10:24:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:973AAFD8-617D-4193-860D-991EDC2188AE
[ThaliCore] Browser.startListening
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:24:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:84CBAF51-7701-48C7-A66C-60F9D0F06178
[ThaliCore] Browser.startListening
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Received state ({"discoveryA,ctive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6A68395F-641E-4852-BA16-E1DD226DE5C4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6A68395F-641E-4852-BA16-E1DD226DE5C4
2017-07-28 1,0:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6A68395F-641E-4852-BA16-E1DD226DE5C4
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD4B2AFD-D8F7-461A-B338-6EDBDFC9258C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FD4B2AFD-D8F7-461A-B338-6EDBDFC9258C
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:32, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(,onPort:errorHandler:) Peer(uuid: "FD4B2AFD-D8F7-461A-B338-6EDBDFC9258C", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:FD4B2AFD-D8F7-461A-B338-6EDBDFC9258C
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FD4B2AFD-D8F7-461A-B338-6EDBDFC9258C
,[ThaliCore] Advertiser.stopAdvertising() peerID:FD4B2AFD-D8F7-461A-B338-6EDBDFC9258C
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:33 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2C90D592-5A1A-4AB3-9831-94152F0137BD
2017-07-28 10:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:37, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-28 10:24:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:6ADD6CB2-78AD-47DF-9D2B-6B0CB8B7A024
[ThaliCore] Browser.startListening
2017-07-28 10:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,t,isingActive":true}'
2017-07-28 10:24:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DF6EC92-4C39-48D4-90E9-D0752BF3BD64:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2C90D592-5A1A-4AB3-9831-94152F0137BD
2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8B8E5E40-BA6B-4AFA-A8E7-23B642839774", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8B8E5E40-BA6B-4AFA-A8E7-23B642839774
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F8DA3440-6F56-4ADA-8858-5EA283505900
[ThaliCore] Browser.startListening
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:24:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DF6EC92-4C39-48D4-90E9-D0752BF3BD64:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0)
,2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2DF6EC92-4C39-48D4-90E9-D0752BF3BD64","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4428E5F1-DF44-4A45,-AACC-1ED6AAD9FC24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24", generation: 0)
,2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2DF6EC92-4C39-48D4-90E9-D0752BF3BD64 (syncValue: f8MECyp49M4YUgahX7oMxsxQEKjz0Ir5)'
,2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2DF6EC92-4C39-48D4-90E9-D0752BF3BD64:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24","generation":0}'
2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2DF6EC92-4C39-48D4-90E9-D0752BF3BD64:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
2017-07-28 10:24:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A","generation":0}'
2017-07-28 10:24:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8B8E5E40-BA6B-4AFA-A8E7-23B642839774:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8B8E5E40-BA6B-4AFA-A8E7-23B642839774", generation: 0)
2017-07-28 10:24:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FDF967AF-AC1F-48BB-BDA5-DC0E81797566","generation":0}'
,2017-07-28 10:24:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:24:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DF6EC92-4C39-48D4-90E9-D0752BF3BD64:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2D,F6EC92-4C39-48D4-90E9-D0752BF3BD64:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:24:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"f8MECyp49M4YUgahX7oMxsxQEKjz0Ir5","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'f8MECyp49M4YUgahX7oMxsxQEKjz0Ir5', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:24:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A (syncValue: cEZuwqWVo1c195OOTwg72QGpuGehs1r0)'
,2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2DF6EC92-4C39-48D4-90E9-D0752BF3BD64:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65167
,2017-07-28 10:24:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cEZuwqWVo1c195OOTwg72QGpuGehs1r0","error":null,"portNumber":65167}'
,2017-07-28 10:24:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cEZuwqWVo1c195OOTwg72QGpuGehs1r0', error: 'null', listeningPort: '65167''
,2017-07-28 10:24:47 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-28 10:24:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 ,10:24:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-28 10:24:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8B8E5E40-BA6B-4AFA-A8E7-2,3B642839774
2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65167
[ThaliCore] Session.disconnect() p,eer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA
2017-07-28 1,0:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:686215DE-C39C-468F-A1DE-C360CB2CBF2F
[Thal,i,Core] Browser.startListening
2017-07-28 10:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:24:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:50 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
2017-07-28 10:24:51 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7","generation":0}'
2017-07-28 10:24:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7, (syncValue: 5VXtfuLwJDHz8CSdEdAApSsXa0YS4Xvk)'
2017-07-28 10:24:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA,3F8F7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
,2017-07-28 10:24:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F84CD8E8-8996-4FBF-892D-97FE4B025995","generation":0}'
,2017-07-28 10:24:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:24:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65171
,2017-07-28 10:24:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5VXtfuLwJDHz8CSdEdAApSsXa0YS4Xvk","error":null,"portNumber":65171}'
,2017-07-28 10:24:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5VXtfuLwJDHz8CSdEdAApSsXa0YS4Xvk', error: 'null', listeningPort: '65171''
,Connecting to the localhost:65171
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
Connected to the localhost:65171
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
,2017-07-28 10:24:54 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-28 10:24:54 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-28 10:25:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA
2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10,:,25:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65171
[ThaliCore] Session.disconnect() p,eer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:25:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5VXtfuLwJDHz8CSdEdAApSsXa0YS4Xvk","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:39056CDE-F8B9-4D96-B071-8452DE2C822B
2017-07-28 1,0:25:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B
[ThaliCore] Browser.startListe,ning
2017-07-28 10:25:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:25:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisi,ngStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
2017-07-28 10:25:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F84CD8E8-8996-4FBF-892D-97FE4B025995","generation":0}'
2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F84CD8E8-8996-4FBF-892D-97FE4B025995, (syncValue: uDIYETXJ4kCuqzuaEE7Idbo6bJE7vB3h)'
2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B0,25995", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7","generation":0}'
2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
2017-07-28 10:25:07 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C4A28E9-2035-47E8-A153-BA2B2523267F","generation":0}'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DE573A-0E5A-4BD7-B7BC-01111EFB454A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D6DE573A-0E5A-4BD7-B7BC-01111EFB454A", generation: 0)
2017-07-28 10:25:07 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D6DE573A-0E5A-4BD7-B7BC-01111EFB454A","generation":0}'
2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:07 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F8,4CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9
[ThaliCore] Advertiser: session connected Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:didReceive,:withName:fromPeer:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9
[ThaliCore] Session.disconnect() peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] Session.startOutputStream(with:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9
[ThaliCore] Browser: sessi,on notConnected retry count #2 for Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.deinit peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9
[ThaliCore] Session.startOutputStream(with:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9
[ThaliCore] Session.startOutputStream(with:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 2, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received (13312 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [1, 2, 4]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received (13099 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F8,4CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:F84CD8E8,-8996-4FBF-892D-97FE4B025995 error: max retries exceeded
2017-07-28 10:25:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uDIYETXJ4kCuqzuaEE7Idbo6bJE7vB3h","error":"Connection could not be established","portNumber":null}'
2017-0,7-28 10:25:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uDIYETXJ4kCuqzuaEE7Idbo6bJE7vB3h', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-28 10:25:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-28 10:25:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7 (syncValue: pfk6Qgt,HTSGljbnLksoMQnjXfaPSKGOm)'
2017-07-28 10:25:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3D93E1A-81F0,-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:25:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-28 10:25:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pfk6QgtHTSGljbnLksoMQnjXfaPSKGOm","error":"Peer is unavailable","portNumber":null}'
,2017-07-28 10:25:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pfk6QgtHTSGljbnLksoMQnjXfaPSKGOm', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:25:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-28 10:25:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4C4A28E9-2035-47E8-A153-BA2B2523267F (syncValue: 66Xxby72Uc3YffPPys5qeHY6pRi799JM)'
,2017-07-28 10:25:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:25:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65184
,2017-07-28 10:25:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"66Xxby72Uc3YffPPys5qeHY6pRi799JM","error":null,"portNumber":65184}'
,2017-07-28 10:25:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '66Xxby72Uc3YffPPys5qeHY6pRi799JM', error: 'null', listeningPort: '65184''
,Connecting to the localhost:65184
,Connecting to the localhost:65184
Connecting to the localhost:65184
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(wi,th:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] Session.startOutputStream(with:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
,Connected to the localhost:65184
,Connected to the localhost:65184
,Connected to the localhost:65184
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 2, 5]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 2, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 2, 5, 6, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [1, 2, 5, 7]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [1, 2, 7]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:7
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:7 [1, 2]
,ok 96 got the same data back
,# teardown
,2017-07-28 10:25:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:25:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:25:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:39056CDE-F8B9-4D96-B071-8452DE2C822B
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:25:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:4C4A28E9-2035-47E8-A153-BA2B2523267F
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65184
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:25:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"66Xxby72Uc3YffPPys5qeHY6pRi799JM","error":"Session disconnected","portNumber":null}'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8817D8DE-3A96-471E-BCE8-28B15E159AEF
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4E10EA18-052F-4852-871C-DB44FA9E3D93
[ThaliCore] Browser.startListening
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:25:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:25:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
2017-07-28 10:25:31 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C4A28E9-2035-47E8-A153-BA2B2523267F","generation":0}'
2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4C4A28E9-2035-47E8-A153-BA2B2523267F, (syncValue: 0VjqCUgBqqNdPKK7zfiWYDdcNoYxZ7HX)'
2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B252,3267F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DE573A-0E5A-4BD7-B7BC-01111EFB454A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D6DE573A-0E5A-4BD7-B7BC-01111EFB454A", generation: 0)
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D6DE573A-0E5A-4BD7-B7BC-01111EFB454A","generation":0}'
2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2923606D-3F00-4705-8BE9-987546819CD0","generation":0}'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7EB6E114-08CB-40BC-BC8E-AF9C5927C203","generation":0}'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4C,4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4C,4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D6DE573A-0E5A-4BD7-B7BC-01111EFB454A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D6DE573A-0E5A-4BD7-B7BC-01111EFB454A", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4C,4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:25:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0VjqCUgBqqNdPKK7zfiWYDdcNoYxZ7HX","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:25:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0VjqCUgBqqNdPKK7zfiWYDdcNoYxZ7HX', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:25:40 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:25:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2923606D-3F00-4705-8BE9-987546819CD0 (syncValue: ZXRFYFN4CCb25hzCVP2Vm9a,Ne5FE5N1h)'
2017-07-28 10:25:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2923606D-3F00-4705-8BE9-98754,6819CD0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:25:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EA691BFE-D9C4-433B-A70E-C9ECD613FE4D
[ThaliCore] Advertiser: session connected Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EA691BFE-D9C4-433B-A70E-C9ECD613FE4D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65200
,2017-07-28 10:25:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZXRFYFN4CCb25hzCVP2Vm9aNe5FE5N1h","error":null,"portNumber":65200}'
,2017-07-28 10:25:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZXRFYFN4CCb25hzCVP2Vm9aNe5FE5N1h', error: 'null', listeningPort: '65200''
,Connecting to the localhost:65200
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:65200
,2017-07-28 10:25:43 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-28 10:25:43 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:8 [1]
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EA691BFE-D9C4-433B-A70E-C9ECD613FE4D
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA691BFE-D9C4-433B-A70E-C9ECD613FE4D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EA691BFE-D9C4-433B-A70E-C9ECD613FE4D
[ThaliCore] Session.startOutputStream(with:) peer:EA691BFE-D9C4-433B-A70E-C9ECD613FE4D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [1, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-28 10:25:44 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-28 10:25:44 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-28 10:25:44 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-28 10:25:44 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-28 10:25:44 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [1]
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA691BFE-D9C4-433B-A70E-C9ECD613FE4D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:EA691BFE-D9C4-433B-A70E-C9ECD613FE4D
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:EA691BFE-D9C4-433B-A70E-C9ECD613FE4D
,2017-07-28 10:25:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:8817D8DE-3A96-471E-BCE8-28B15E159AEF
2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10,:,25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:2923606D-3F00-4705-8BE9-987546819CD0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65200
[ThaliCore] Session.disconnect() p,eer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:25:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:61F798BB-B8AE-4376-B306-D7BF1030062F
,2017-07-28 10:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:25:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browse,r.init(serviceType:foundPeer:lostPeer:) peer:8DCA9EAC-1029-4927-ABDA-5384845F716B
[ThaliCore] Browser.startListening
2017-07-28 10:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive",:true}'
,2017-07-28 10:25:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-28 10:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
2017-07-28 10:25:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2923606D-3F00-4705-8BE9-987546819CD0","generation":0}'
,2017-07-28 10:25:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2923606D-3F00-4705-8BE9-987546819CD0 (syncValue: dO95fBlzPm2fUQWQJgaDWUCX5xuf3lMx)'
2017-07-28 10:25:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:25:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7EB6E114-08CB-40BC-BC8E-AF9C5927C203","generation":0}'
2017-07-28 10:25:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,28 10:25:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
2017-07-28 10:25:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2DEF4005-6540-42F4-B0CD-F8B75F1A30AB","generation":0}'
2017-07-28 10:25:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:54 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
2017-07-28 10:25:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2","generation":0}'
2017-07-28 10:25:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:54 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:25:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:29,23606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,923606D-3F00-4705-8BE9-987546819CD0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:29,23606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,923606D-3F00-4705-8BE9-987546819CD0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:29,23606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,923606D-3F00-4705-8BE9-987546819CD0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:26:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dO95fBlzPm2fUQWQJgaDWUCX5xuf3lMx","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:26:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dO95fBlzPm2fUQWQJgaDWUCX5xuf3lMx', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:26:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-28 10:26:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2DEF4005-6540-42F4-B0CD-F8B75F1A30AB (syncValue: fCycVpmDn6hz0evvO9QCFb15Tz4OBRDO)'
,2017-07-28 10:26:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:26:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65215
2017-07-28 10:26:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fCycVpmDn6hz0evvO9QCFb15Tz4OBRDO",,"error":null,"portNumber":65215}'
2017-07-28 10:26:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fCycVpmDn6hz0evvO9QCFb15Tz4OBRDO', error: 'null', listeningPort: '65215''
,Connecting to the localhost:65215
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
,Connected to the localhost:65215
,2017-07-28 10:26:02 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-28 10:26:02 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6F8CB1E9-0556-4BD5-AFFE-3C9FA640F5B9
[ThaliCore] Advertiser: session connected Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6F8CB1E9-0556-4BD5-AFFE-3C9FA640F5B9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6F8CB1E9-0556-4BD5-AFFE-3C9FA640F5B9
,[ThaliCore] Session.session(_:peer:didChange:) peer:6F8CB1E9-0556-4BD5-AFFE-3C9FA640F5B9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6F8CB1E9-0556-4BD5-AFFE-3C9FA640F5B9
[ThaliCore] Session.startOutputStream(with:) peer:6F8CB1E9-0556-4BD5-AFFE-3C9FA640F5B9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (54586 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [1, 11]
,ok 102 got the same data back
,# teardown
,2017-07-28 10:26:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 ,10:26:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:61F798BB-B8AE-4376-B306-D,7BF1030062F
2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65215
[ThaliCore] Session.disconnect() peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6F8CB1E9-0556-4BD5-AFFE-3C9FA640F5B9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6F8CB1E9-0556-4BD5-AFFE-3C9FA640F5B9
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:6F8CB1E9-0556-4BD5-AFFE-3C9FA640F5B9
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CD8C0BA6-8739-4075-8FFC-DCCAB3784FA9
,[ThaliCore] Browser.startListening
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:26:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6230A678-BDFC-47EE-97B5-B204F76EEA87
,2017-07-28 10:26:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:26:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:26:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
,2017-07-28 10:26:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2","generation":0}]'
2017-07-28 10:26:20 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2","generation":0}'
,2017-07-28 10:26:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-28 10:26:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"pe,erAvailable":true,"peerIdentifier":"2DEF4005-6540-42F4-B0CD-F8B75F1A30AB","generation":0}]'
2017-07-28 10:26:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2DEF4005-6540-42F4-B0C,D-F8B75F1A30AB","generation":0}'
,2017-07-28 10:26:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BC20BFCE-89C5-4087-9DBF-512405597B19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BC20BFCE-89C5-4087-9DBF-512405597B19", generation: 0)
2017-07-28 10:26:21 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BC20BFCE-89C5-4087-9DBF-512405597B19","generation":0}]'
2017-07-28 10:26:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"BC20BFCE-89C5-4087-9DBF-512405597B19","generation":0}'
2017-07-28 10:26:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
2017-07-28 10:26:24 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2DEF4005-6540-42F4-B0CD-F8B75F1A30AB","generation":0}]'
2017-07-28 10:26:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"2DEF4005-6540-42F4-B0CD-F8B75F1A30AB","generation":0}'
2017-07-28 10:26:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:26:25 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:25 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6230A678-BDFC-47EE-97B5-B204F76EEA87
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWra,pper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:25 - DEBUG thaliMobileNati,v,eWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-28 10:26:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5B7BACFB-8A8C-4837-B6B2-844D2F6A7CBB
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "45DBE256-279E-4763-BEFE-F49262CF3EFF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:45DBE256-279E-4763-BEFE-F49262CF3EFF
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:45DBE256-279E-4763-BEFE-F49262CF3EFF
ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-28 10:26:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-28 10:26:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-28 10:26:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-28 10:26:27 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-28 10:26:27 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-28 10:26:27 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9bfd9faf-52f5-4d28-b42f-8df4c25526f9 error: startListeningNotActive
2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2D5H59isDXv2U5,UuXqNFwPwXUSxGxxJX","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:88D79D27-FB39-450A-8385-E7039093A95B
[ThaliCore] Browser.startListening
2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:26:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VCTwb9oc2iTv9lRggxSVqFph8OcsDUEd","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect ,returned
ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-28 10:26:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C3137B6A-E36A-44BF-9A39-6EF5D4A148DD
,[ThaliCore] Browser.startListening
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:26:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:94135033-0ad4-4912-b439-fcd07a8b3c1a
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FE8EAE0C-6391-48F3-99B5-6FCC3C505E23
2017-07-28 1,0:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:26:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9BF9E82E-695C-411E-AAA6-81F0E3D64ACD
[Thal,iCore] Browser.startListening
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:26:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
,2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BC20BFCE-89C5-4087-9DBF-512405597B19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BC20BFCE-89C5-4087-9D,BF-512405597B19", generation: 0)
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2","generation":0}'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2 (syncValue: V0eZGR1oOuYFu29C3bZFqPa2JXJ1kE5x)'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BC20BFCE-89C5-4087-9DBF-512405597B19","generation":0}'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
2017-07-28 10:26:32 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FC4C696C-75CA-4D68-9DED-BD4676EDB25B","generation":0}'
2017-07-28 10:26:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:26:32 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:26:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE8EAE0C-6391-48F3-99B5-6FCC3C505E23:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
,2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5A32A711-3AC9-4795-86B0-CC719851C109","generation":0}'
,2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BC20BFCE-89C5-4087-9DBF-512405597B19:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BC20BFCE-89C5-4087-9DBF-512405597B19", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:44,1E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,41E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:44,1E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,41E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-28 10:26:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"V0eZGR1oOuYFu29C3bZFqPa2JXJ1kE5x","error":"Peer is unavailable","portNumber":null}'
,2017-07-28 10:26:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'V0eZGR1oOuYFu29C3bZFqPa2JXJ1kE5x', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:26:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-28 10:26:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FC4C696C-75CA-4D68-9DED-BD4676EDB25B (syncValue: jHpdFS39UDLL2WgW9U6DeuDPyw0NE4Xy)'
,2017-07-28 10:26:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:26:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65229
,2017-07-28 10:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jHpdFS39UDLL2WgW9U6DeuDPyw0NE4Xy","error":null,"portNumber":65229}'
,2017-07-28 10:26:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jHpdFS39UDLL2WgW9U6DeuDPyw0NE4Xy', error: 'null', listeningPort: '65229''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0) found active relay
,2017-07-28 10:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IKcqd0l3gSYn8PR8mdGHoxKtX31Q6zL2","error":null,"portNumber":65229}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
ok 144 No error
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 11, 12]
ok 145 Ports equal
[ThaliCore] BrowserRelay.didOpenVi,rtualSocketStreamsHandler
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0) found active relay
,2017-07-28 10:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tspgx05bK7VqECTaC6OHcyQ0mLqSsoGp","error":null,"portNumber":65229}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,2017-07-28 10:26:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 ,10:26:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-28 10:26:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FE8EAE0C-6391-48F3-99B5-6,FCC3C505E23
2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65229
[ThaliCore] VirtualSocket.closeStr,eams() vsID:12
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] Session.disconnect() peer:FC4C696C-75CA-4D68-,9DED-BD4676EDB25B:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 11]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.d,einit peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-28 10:26:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:47 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-28 10:26:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-28 10:26:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-28 10:26:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-28 10:26:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-28 10:26:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-28 10:26:51 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:51 - DEBUG createNativeListener: 'listening 65232'
,ok 149 Should throw
,# teardown
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'listening 65234'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'listening 65237'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'listening 65241'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'listening 65246'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - close'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 65250'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 65254'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 65258'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 65262'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'listening 65314'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'listening 65318'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 193 serversManager must not be null
ok 194 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 195 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:57 - DEBUG createNativeListener: 'listening 65321'
ok 196 port must be in range
,# teardown
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'listening 65322'
,ok 197 second start should return same port
,# teardown
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'listening 65324'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-28 10:26:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-28 10:26:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-28 10:26:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 65326
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BBF8648D-CF32-4B35-8271-410FDEA09399
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:26:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:511BFC48-3654-43A0-B9A7-3340033,82552
,[ThaliCore] Browser.startListening
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:26:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
,2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5A32A711-3AC9-4795-86B0-CC719851C109","generation":0}'
,2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5A32A711-3AC9-4795-86B0-CC719851C109 (syncValue: 28f3S75YSbxcTDmSmuwb21EvdPz9dz1d)'
,2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
,2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D","generation":0}'
,2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
2017-07-28 10:27:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"93BE8C3D-4DB1-49AB-B941-42D47D125E6C","generation":0}'
2017-07-28 10:27:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:27:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:27:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A32A711-3AC9-4795-86B0-CC719851C109:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,A32A711-3AC9-4795-86B0-CC719851C109", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA
[ThaliCore] Advertiser: session connected Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A32A711-3AC9-4795-86B0-CC719851C109:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,A32A711-3AC9-4795-86B0-CC719851C109", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:27:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"28f3S75YSbxcTDmSmuwb21EvdPz9dz1d","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:27:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '28f3S75YSbxcTDmSmuwb21EvdPz9dz1d', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:27:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:27:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D (syncValue: 0LGamEgcPyAPLHgON4zqwzCAAcm0McIr)'
2017-07-28 10:27:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3ABAD824-E122-4F0A-9CF1-28EC8,A70BE0D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:27:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB174017-018E-4451-84F9-48C81BD7147D
[ThaliCore] Advertiser: session connected Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DB174017-018E-4451-84F9-48C81BD7147D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DB174017-018E-4451-84F9-48C81BD7147D
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB174017-018E-4451-84F9-48C81BD7147D state: connecting -> connected
[ThaliCore] Session.session(_:peer:didChange:) peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0 state: connecting -> connected
[ThaliCore] ,Browser: session connected to Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65336
,2017-07-28 10:27:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0LGamEgcPyAPLHgON4zqwzCAAcm0McIr","error":null,"portNumber":65336}'
,2017-07-28 10:27:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0LGamEgcPyAPLHgON4zqwzCAAcm0McIr', error: 'null', listeningPort: '65336''
,ok 210 should be equal
,2017-07-28 10:27:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 93BE8C3D-4DB1-49AB-B941-42D47D125E6C (syncValue: 0I9LjnJ1fPrEDVsHO42dnSTwMyM3QFUK)'
,2017-07-28 10:27:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65340
2017-07-28 10:27:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0I9LjnJ1fPrEDVsHO42dnSTwMyM3QFUK",,"error":null,"portNumber":65340}'
2017-07-28 10:27:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0I9LjnJ1fPrEDVsHO42dnSTwMyM3QFUK', error: 'null', listeningPort: '65340''
,ok 211 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 ,10:27:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-28 10:27:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BBF8648D-CF32-4B35-8271-4,10FDEA09399
2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65336
[ThaliCore] Session.disconnect() p,eer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65340
,[ThaliCore] Session.disconnect() peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DB174017-018E-4451-84F9-48C81BD7147D
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB174017-018E-4451-84F9-48C81BD7147D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] Session.deinit peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserRelay.deinit
2017-07-28 10:27:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,# Multiple local http requests
,listening on 65342
,[ThaliCore] Session.deinit peer:DB174017-018E-4451-84F9-48C81BD7147D
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:27:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28, 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:95F44C45-7F4B-4ED1-94A3-C1753634B03C
2017-07-28 1,0:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E
[Tha,l,iCore] Browser.startListening
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:27:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"93BE8C3D-4DB1-49AB-B941-42D47D125E6C","generation":0}'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 93BE8C3D-4DB1-49AB-B941-42D47D125E6C (syncValue: a3xaq6s3qeysZzn1zZkjfXO7oYTEYfF7)'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D","generation":0}'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
2017-07-28 10:27:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}'
2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:27:15 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
,2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","generation":0}'
,2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:93,BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,3BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:93,BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,3BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:20DA17E9-8905-46E1-B602-144EB1DA4CFF
[ThaliCore] Advertiser: session connected Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:20DA17E9-8905-46E1-B602-144EB1DA4CFF state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:93,BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,3BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:20DA17E9-8905-46E1-B602-144EB1DA4CFF
,[ThaliCore] Session.session(_:peer:didChange:) peer:20DA17E9-8905-46E1-B602-144EB1DA4CFF state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B
[ThaliCore] Advertiser: session connected Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:93,BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:93BE8C3D,-4DB1-49AB-B941-42D47D125E6C error: max retries exceeded
2017-07-28 10:27:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"a3xaq6s3qeysZzn1zZkjfXO7oYTEYfF7","error":"Connection could not be established","portNumber":null}'
2017-0,7-28 10:27:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'a3xaq6s3qeysZzn1zZkjfXO7oYTEYfF7', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-28 10:27:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-28 10:27:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7CEF816A-6CE4-449C-8991-54BCD7BAA133 (syncValue: 0kWMzyY,CogKctYFSf3tTlgyXiJPVYMqk)'
2017-07-28 10:27:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7CEF816A-6CE4,-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:27:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:27:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B
,[ThaliCore] Session.session(_:peer:didChange:) peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65360
,2017-07-28 10:27:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0kWMzyYCogKctYFSf3tTlgyXiJPVYMqk","error":null,"portNumber":65360}'
,2017-07-28 10:27:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0kWMzyYCogKctYFSf3tTlgyXiJPVYMqk', error: 'null', listeningPort: '65360''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-28 10:27:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 95F29FF2-0D10-45FD-BF02-EBCF261CB31F (syncValue: DLMMeSqThEMmeHGtgX1dsTdxFYxwUTtl)'
,2017-07-28 10:27:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65367
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DLMMeSqThEMmeHGtgX1dsTdxFYxwUTtl","error":null,"portNumber":65367}'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DLMMeSqThEMmeHGtgX1dsTdxFYxwUTtl', error: 'null', listeningPort: '65367''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:95F44C45-7F4B-4ED1-94A3-C1753634B03C
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65360
[ThaliCore] Session.disconnect() peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65367
,[ThaliCore] Session.disconnect() peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:20DA17E9-8905-46E1-B602-144EB1DA4CFF state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B
,[ThaliCore] Session.deinit peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:27:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B
,[ThaliCore] AdvertiserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-28 10:27:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 227 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'listening 65371'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3C61FA37-8B88-44EB-BF5C-7E50FE10BBEB
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}'
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","generation":0}]'
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F",",generation":0}'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:33 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:33 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:27:33 - DEBUG makeIntoCloseAllServer: 'closeAll called, ,on server'
,ok 230 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'listening 65372'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "98D20A83-3AFF-4509-8DCB-20D59181A02D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:98D20A83-3AFF-4509-8DCB-20D59181A02D
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "98D20A83-3AFF-4509-8DCB-20D59181A02D", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:98D20A83-3AFF-4509-8DCB-20D59181A02D
2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:34, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:98D20A83-3AFF-4509-8DCB-20D59181A02D
[ThaliCore] Advertiser.stopAdvertising() peerID:98D20A83-3AFF-4509-8DCB-20D59181A02D
2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpda,teNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-28 10:27:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 233 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'listening 65375'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 236 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 237 network status should have certain non-empty properties
,# teardown
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-28 10:27:35 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 239 specific error expected
,# teardown
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'listening 65376'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7BBB3643-38DC-4116-97A4-8F1A57F67E1E
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C14D5717-237E-4DE5-8E42-045873BBFE61", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C14D5717-237E-4DE5-8E42-045873BBFE61
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 241 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:C14D5717-237E-4DE5-8E42-045873BBFE61
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:27:35 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'listening 65379'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:28E8877B-3891-4A4C-A242-4152547A6ACC
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "994D9C44-2C1F-4517-A466-65182169A8A5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:994D9C44-2C1F-4517-A466-65182169A8A5
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 243 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:994D9C44-2C1F-4517-A466-65182169A8A5
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-28 10:27:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'listening 65381'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:88CE7DC9-1C16-4D2E-86A1-677223749ED2
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3A0542FD-68CB-4A07-A610-94131C38229F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3A0542FD-68CB-4A07-A610-94131C38229F
2017-07-28 1,0:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3A0542FD-68CB-4,A07-A610-94131C38229F
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 245 is stopped after calling stop
,ok 246 connection should fail after stopping
,# teardown
,ok 247 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-28 10:27:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 248 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 249 error description matches
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-28 10:27:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 251 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 252 error description matches
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 254 IMPLEMENT ME!!!!!!
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-28 10:27:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 256 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:39 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-28 10:27:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-28 10:27:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-28 10:27:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 260 NOT IMPLEMENTED # SKIP
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-28 10:27:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 262 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-28 10:27:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-28 10:27:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 264 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-28 10:27:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 65384'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:679196F9-F6AE-448D-8454-604824D25748
[ThaliCore] Browser.startListening
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 266 discoveryActive ,matches
ok 267 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,2017-07-28 10:27:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 65385'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1386132F-EEC8-4C1B-8BFD-6A12449C23DE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1386132F-EEC8-4C1B-8BFD-6A12449C23DE
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:1386132F-EEC8-4C1B-8BFD-6A12449C23DE
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 65387'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 274 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 65388'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F89BCCF4-5E51-4228-BAAE-15D5BDF9F505
[ThaliCore] Browser.st,artListening
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-89,91-54BCD7BAA133","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","generation":0}]'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","generation":0}'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 275 portNumber equal null
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F7FB3F7D-6098-45DE-996C-3806B0585C2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F7FB3F7D-6098-45DE-996C-3806B0585C2A", generation: 0)
,2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F7FB3F7D-6098-45DE-996C-3806B0585C2A","generation":0}]'
,2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F7FB3F7D-6098-45DE-996C-3806B0585C2A","generation":0}'
,2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F7FB3F7D-6098-45DE-996C-3806B0585C2A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F7FB3F7D-6098-45DE-996C-3806B0585C2A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A", generation: 0)
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A","generation":0}]'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A","generation":0}'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:44 - I,NFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":,null}})'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-28 10:27:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-28 10:27:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 277 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:44 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-28 10:27:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-28 10:27:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 279 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'listening 65390'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:33B53FAA-55A2-4C6A-AF54-F1FDCDD345B5
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:16CAC7EF-BA00-4A94-865C-8B233DBD72F1
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:27:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:0323044D-1913-4454-B736-375476473E4A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}]'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","generation":0}]'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","generation":0}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 66D1520A-8B85-4C7C-98D7-E64579619E08 (syncValue: UFqeiIHgU5gFRJZUseZZunLhxetTFmZP)'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65393
2017-07-28 10:27:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UFqeiIHgU5gFRJZUseZZunLhxetTFmZP",,"error":null,"portNumber":65393}'
2017-07-28 10:27:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UFqeiIHgU5gFRJZUseZZunLhxetTFmZP', error: 'null', listeningPort: '65393''
,2017-07-28 10:27:49 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 11, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:27:49 - DEBUG testUtils: 'Got response data'
,2017-07-28 10:27:49 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
,ok 282 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:16CAC7EF-BA00-4A94-865C-8B233DBD72F1
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:27:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:66D1520A-8B85-4C7C-98D7-E64579619E08
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65393
[ThaliCore] VirtualSocket.closeStr,eams() vsID:13
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] Session.disconnect() peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:13 [1, 1,1]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 284 FIX ME, PLEASE!!!
,# teardown
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-28 10:27:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-28 10:27:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:59 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:27:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 288 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 289 specific error should be returned
,# teardown
,2017-07-28 10:28:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28, 10:28:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F7FB3F7D-6098-45DE-996C-3806B0585C2A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28 10:28:00 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28 10:28:00 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28 10:28:00 - DEBUG thaliMobile,:, 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-28 10:28:00 - DEBUG thaliMobileNativeWrapper: 'listening 65395'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 297 error should be null
,ok 298 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 301 error should be null
,ok 302 error should be null
,# setup
,ok 303 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'listening 65396'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C26B2938-7024-4C59-B026-970A3D4C4896
[ThaliCore] Browser.startListening
2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 304 error should be null
ok 305 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 306 error should be null
,ok 307 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
# teardown
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}]'
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}'
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:28:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:28:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 308 error should be null
,ok 309 error should be null
,# setup
,ok 310 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'listening 65397'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9D3E394D-3676-41B6-A216-8996BAA70CB7", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:9D3E394D-3676-41B6-A216-8996BAA70CB7
2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 311 error should be null
ok 312 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9D3E394D-3676-41B6-A216-8996BAA70CB7", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:9D3E394D-3676-41B6-A216-8996BAA70CB7
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:9D3E394D-3676-41B6-A216-8996BAA70CB7
[ThaliCore] Advertiser.stopAdvertising() peerID:9D3E394D-3676-41B6-A216-8996BAA70CB7
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
,ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'listening 65400'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 318 error should be null
,ok 319 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 error should be null
,ok 323 error should be null
,# setup
,ok 324 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-28 10:28:02 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 325 This should not cause wifi to fail
,ok 326 native router should be bad
,# teardown
,ok 327 error should be null
,ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'listening 65401'
,ok 330 first call should succeed
ok 331 first call should succeed
ok 332 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 333 error should be null
,ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-28 10:28:03 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 336 error should be null
,ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-28 10:28:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 339 error should be null
ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-28 10:28:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"376e05ef-4ca4-4951-9c50-91fab1a146b1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 342 should be called once
,ok 343 should not have been called more than once
,# teardown
,2017-07-28 10:28:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"376e05ef-4ca4-4951-9c50-91fab1a146b1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"38c7e7eb-1028-4a3f-84a7-74926e03d68b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 352 peer should be available
,ok 353 cache contains native peer
,2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"38c7e7eb-1028-4a3f-84a7-74926e03d68b","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 354 peer should be unavailable
,ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
,2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5d279b82-98a0-4b57-a2b1-a0a8f9a95d62","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 360 peer should be available
,ok 361 cache contains wifi peer
,2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5d279b82-98a0-4b57-a2b1-a0a8f9a95d62","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 362 peer should be unavailable
,ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
,ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a57c7cf4-265d-44a3-9934-5fbc2af33da2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 367 first peer is a,vailable
2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1d87b551-4dc5-4f5c-abf1-c82855dd9d05","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 368 second, peer is available
ok 369 first and second peers are different
,# teardown
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a57c7cf4-265d-44a3-9934-5fbc2af33da2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1d87b551-4dc5-4f5c-abf1-c82855dd9d05","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
,ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a0b8431d-9cd9-4201-b61f-a3fecbb0f81b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 peer is available
,# teardown
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a0b8431d-9cd9-4201-b61f-a3fecbb0f81b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 375 error should be null
ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-28 10:28:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 378 error should be null
ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-28 10:28:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 381 error should be null
ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"157e8e24-511e-424a-9679-daf2f7a15598","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 384 peer should be ,available
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"157e8e24-511e-424a-9679-daf2f7a15598","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 385 peer should be ,available
ok 386 should store correct generation
,# teardown
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"157e8e24-511e-424a-9679-daf2f7a15598","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'listening 65402'
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83b0862a-a254-4dce-85c2-4d5af48d11be","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 390 discovered correct peer
,ok 391 got correct generation
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83b0862a-a254-4dce-85c2-4d5af48d11be","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,# teardown
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"83b0862a-a254-4dce-85c2-4d5af48d11be","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 394 error should be null
,ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'listening 65403'
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"44159aec-9d17-4b2a-a001-46e991528f23","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 397 discovered available peer
,ok 398 peer is available
,# teardown
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"44159aec-9d17-4b2a-a001-46e991528f23","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 399 error should be null
,ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0a649142-719e-4bd3-b96d-284be1a9478e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 402 peer should be ,available
2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0a649142-719e-4bd3-b96d-284be1a9478e","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 403 peer should be unavailable
ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
,ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-28 10:28:08 - DEBUG thaliMobileNativeWrapper: 'listening 65404'
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cac87d81-6e98-446a-964c-f469b9d47a87","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 first peer is expected to be available
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9eea7c22-c841-4d8a-a145-f7b4b08d923f","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 409 second peer is expected to be available
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9eea7c22-c841-4d8a-a145-f7b4b08d923f","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 peer became unavailable
,ok 411 it was wifi peer
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9eea7c22-c841-4d8a-a145-f7b4b08d923f","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 412 we found peer again
,ok 413 it was wifi peer
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9eea7c22-c841-4d8a-a145-f7b4b08d923f","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 414 peer became unavailable
,ok 415 it was wifi peer
,# teardown
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cac87d81-6e98-446a-964c-f469b9d47a87","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 416 error should be null
,ok 417 error should be null
,# setup
,ok 418 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-28 10:28:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 419 error should be null
ok 420 error should be null
,# setup
,ok 421 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-28 10:28:09 - DEBUG thaliMobileNativeWrapper: 'listening 65405'
,2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5d5fdbce-83b1-4135-a6b9-51acf360d22c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 422 first peer is expected to be available
,2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"40e5111b-560b-42ae-a130-c8c5c9f72710","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 423 second peer is expected to be available
,2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5d5fdbce-83b1-4135-a6b9-51acf360d22c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 424 peer became unavailable
,2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"40e5111b-560b-42ae-a130-c8c5c9f72710","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 425 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 426 error should be null
,ok 427 error should be null
,# setup
,ok 428 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-28 10:28:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 429 error should be null
ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-28 10:28:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 432 error should be null
ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c701e96-9b59-495f-a6b0-99488c829f57","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 435 peer discovered ,first time does not have new address
2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c701e96-9b59-495f-a6b0-99488c829f57","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 436 address has not been changed
2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c701e96-9b59-495f-a6b0-99488c829f57","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
,ok 437 new port handled correctly
2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c701e96-9b59-495f-a6b0-99488c829f57","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPo,rt":true}'
ok 438 new host handled correctly
2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c701e96-9b59-495f-a6b0-99488c829f57","connectionType":"tcp","peerAvailable":false,"generation":20,,"newAddressPort":null}'
,ok 439 newAddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
,ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-28 10:28:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 443 error should be null
ok 444 error should be null
,# setup
,ok 445 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 446 NOT IMPLEMENTED # SKIP
,# teardown
,ok 447 error should be null
,ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-28 10:28:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
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
,2017-07-28 10:28:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 457 error should be null
,ok 458 error should be null
,# setup
,ok 459 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 460 contains expected properties
,ok 461 the same hostAddress
,ok 462 the same portNumber
,# teardown
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 463 error should be null
,ok 464 error should be null
,# setup
,ok 465 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 466 contains expected properties
ok 467 the same hos,tAddress
ok 468 the same portNumber
,# teardown
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
,ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'listening 65406'
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"01391b08-b86b-41f2-ba45-461925e62da1","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 472 Got specific error message
,# teardown
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"01391b08-b86b-41f2-ba45-461925e62da1","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'listening 65407'
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c96f2ac4-0795-4c1d-bbe2-9c416977a6d6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:c96f2ac4-0795-4c1d-bbe2-9c416977a6d6
,ok 476 native wrapper `disconnect` called once
,ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-28 10:28:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c96f2ac4-0795-4c1d-bbe2-9c416977a6d6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 478 error should be null
,ok 479 error should be null
,# setup
,ok 480 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-28 10:28:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 481 error should be null
,ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-28 10:28:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 484 error should be null
,ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-28 10:28:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 487 error should be null
ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-28 10:28:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 490 error should be null
,ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-28 10:28:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 493 error should be null
,ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-28 10:28:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 496 error should be null
,ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-28 10:28:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'listening 65408'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1221CCB7-6260-4DE1-B917-07C3E03BD6F1
,[ThaliCore] Browser.startListening
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"95e16013-f9fc-411d-9c5d-ed9b70d42265","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ab7cb7bd-dd6e-4e12-9e35-de731c14b0f8","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 503 Peer availabilities has one entry for our connection type
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"95e16013-f9fc-411d-9c5d-ed9b70d42265","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ab7cb7bd-dd6e-4e12-9e35-de731c14b0f8","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}]'
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}'
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 504 No peers
,ok 505 No peers
,ok 506 No peers
,# teardown
,ok 507 error should be null
,ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'listening 65409'
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7962f4a4-9721-4639-8d74-a621b4b7e1ac","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 510 1
,ok 511 2
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fe3bf5b5-c97e-4ebb-9258-7b31d0763f91","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7962f4a4-9721-4639-8d74-a621b4b7e1ac","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fe3bf5b5-c97e-4ebb-9258-7b31d0763f91","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 512 error should be null
,ok 513 error should be null
,# setup
,ok 514 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-28 10:28:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 515 error should be null
ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'listening 65410'
ok 518 error should be null
ok 519 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5D,D28772CB37", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37
2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 520 error should be null
ok 521 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:701D18EE-61FC-4884-9394-6931A9342548
[ThaliCore] Browser.startListening
2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 522 error should be null
ok 523 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
,2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}]'
2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}'
,2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:28:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 66D1520A-8B85-4C7C-98D7-E64579619E08 (syncValue: 0)'
,2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}]'
2017-07-28 10:28:18 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:28:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
[ThaliCore] Browser.br,owser(_:foundPeer:withDiscoveryInfo:) found peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","generation":0}]'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","generation":0}'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:28:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5DD28772CB37", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:66,D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,6D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] Advertiser: session connected Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5DD28772CB37", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
,[ThaliCore] Session.session(_:peer:didChange:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
,[ThaliCore] Session.startOutputStream(with:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 11, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:66,D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,6D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:66,D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,6D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:66,D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:66D1520A,-8B85-4C7C-98D7-E64579619E08 error: max retries exceeded
2017-07-28 10:28:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Connection could not be established","portNumber":null}'
,2017-07-28 10:28:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 1)'
,2017-07-28 10:28:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Advertiser: session connected Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5DD28772CB37", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65423
2017-07-28 10:28:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":65423}'
,2017-07-28 10:28:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9D650D87-8C6C-4AED-A3AE-5132A5710C9F (syncValue: 2)'
2017-07-28 10:28:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Session.startOutputStream(with:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 11, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 11, 14, 15, 16]
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:28:31 - DEBUG testUtils: 'Got response data'
,2017-07-28 10:28:31 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65427
,2017-07-28 10:28:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":65427}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 11, 14, 15, 16, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:28:34 - DEBUG testUtils: 'Got response data'
,2017-07-28 10:28:34 - DEBUG testUtils: 'Got end'
,ok 524 received all uuids
,# teardown
,2017-07-28 10:28:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28, 10:28:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28 10:28:35 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.,stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37
2017-07-28 10:28:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
201,7,-07-28 10:28:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-28 10:28:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:28:35 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 525 error should be null
,ok 526 error should be null
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeS,treams() vsID:14
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [1, 11, 14, 15, 17]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [1, 11, 15, 17]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [1, 11, 17]
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[Th,aliCore] VirtualSocket.deinit vsID:17 [1, 11]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconn,ectHandler
,ok 527 ThaliMobile should be stopped
,# test for data corruption
,2017-07-28 10:28:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 528 error should be null
ok 529 error should be null
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
,ok 537 after start
,2017-07-28 10:28:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 538 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 539 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-28 10:28:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 540 clean kill
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 542 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 543 forever agent should have it's own destroy method
,ok 544 agent's destroy should be called
,ok 545 agent's destroy should not be called again
,ok 546 agent is destroyed
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
,ok 567 Entry 2_2 should not be found
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
,2017-07-28 10:28:43 - DEBUG testUtils: 'Got response data'
,2017-07-28 10:28:43 - DEBUG testUtils: 'Got end'
,ok 595 Got expected response
,ok 596 Got psk call back
,# teardown
,2017-07-28 10:28:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 597 is an agent
,ok 598 enqueue worked
,ok 599 is an agent
,ok 600 enqueue 2 worked
,ok 601 enqueue is not available when stopped
,ok 602 start action is killed
,ok 603 killed action is still killed
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
,ok 615 2nd good enqueue
,ok 616 we are in the pool
,ok 617 We are out of the pool
,ok 618 Action was killed
,ok 619 The original kill was called too
,ok 620 second item is still in queue
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
,2017-07-28 10:28:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 631 Got right error
ok 632 Start should not be called
ok 633 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-28 10:28:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-28 10:28:47 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 634 Got right error
,ok 635 Start should not be called
,ok 636 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 637 Got null
2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 638 is an agent
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 639 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 640 Got Null
ok 641 Got another null
2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
ok 642 is an agent
2017-07-28 10:28,:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 643 is an agent
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 644 Action 1 killed at least once
,ok 645 Action 1 went first
,ok 646 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 647 should have gotten null
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 648 Should have stopped nicely
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 649 Still looking for null
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 650 Yup, another null
,ok 651 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 652 Null 1
,ok 653 (unnamed assert)
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 654 is an agent
,ok 655 Null 3
,ok 656 Replication not yet called
,ok 657 Notification 2 not yet called
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 658 is an agent
,ok 659 Notification went first
,ok 660 Notification 2 not called yet
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 661 is an agent
,ok 662 Notification finished
,ok 663 Replication finished
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 664 is an agent
,ok 665 First does not throw
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 666 is an agent
,ok 667 Second does not throw
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 668 is an agent
,ok 669 first ok
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 second ok
,ok 672 third ok
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-28 10:28:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-28 10:28:52 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
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
,2017-07-28 10:28:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-28 10:28:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-28 10:28:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 681 Response should be NETWORK_PROBLEM
,ok 682 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-28 10:28:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 683 Resolution should be BAD_PEER
,ok 684 correct error message
,# teardown
,2017-07-28 10:28:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 685 Call start once
,ok 686 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 687 must return null after successful call.
,# teardown
,2017-07-28 10:28:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 688 Should be Killed
,ok 689 Start after killed
,# teardown
,2017-07-28 10:28:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 690 Should be KILLED
,ok 691 must return null after successful kill
,# teardown
,2017-07-28 10:28:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-07-28 10:29:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 694 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 695 must return null after successful call
,# teardown
,2017-07-28 10:29:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-28 10:29:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 696 Should be NETWORK_PROBLEM caused closing server socket
,ok 697 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 698 Should be NETWORK_PROBLEM caused closing client socket
ok 699 Should be Could not establish TCP connection
,# teardown
,2017-07-28 10:29:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 700 publicKeysToNotify cannot be null
ok 701 ecdh for local device cannot be null
ok 702 milliseconds cannot be less than 0
ok 703 milliseconds cannot be 0
ok 704 milliseconds cannot be greater than one_day
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
,2017-07-28 10:29:14 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 717 should be equal
ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 719 right number of calls to address book
,ok 720 good preAmble
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
ok 733 keys match
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
,ok 741 bluetooth peer's notification has correct connection type
,ok 742 tcp peer's notification has correct connection type
,2017-07-28 10:29:19 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-28 10:29:19 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-28 10:29:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 743 notification peer dictionary contains exactly 1 peer
2017-07-28 10:29:19 - WARN thaliNotificationClient: 'peer is not available'
,ok 744 notification peer dictionary does not contain any peers
,2017-07-28 10:29:19 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-28 10:29:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 745 entry exists
,ok 746 entry is resolved
,# teardown
,2017-07-28 10:29:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 747 Action should be KILLED
,ok 748 Peer state should be RESOLVED
,# teardown
,2017-07-28 10:29:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 749 hostAddress must match
,ok 750 portNumber must match
,ok 751 suggestedTCPTimeout must match
,ok 752 connectionType must match
,ok 753 peerIDs must match
,# teardown
,2017-07-28 10:29:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 754 Correct error
,# teardown
,2017-07-28 10:29:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 755 hostAddress must match
,ok 756 portNumber must match
,ok 757 suggestedTCPTimeout must match
,ok 758 connectionType must match
,ok 759 peerIds must match
,# teardown
,2017-07-28 10:29:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-28 10:29:23 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 760 action should be resolved with NETWORK_PROBLEM error
,2017-07-28 10:29:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 761 action should be resolved with NETWORK_PROBLEM error
,2017-07-28 10:29:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-28 10:29:25 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
ok 764 correct number of requests
ok 765 correct number of failures
ok 766 correct final peer state
,# teardown
,2017-07-28 10:29:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-28 10:29:27 - WARN thaliNotificationClient: 'peer is not available'
2017-07-28 10:29:27 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 peerDictionary should become empty
,# teardown
,2017-07-28 10:29:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-28 10:29:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 768 failed with expected error
ok 769 peer state should be RESOLVED
,# teardown
,2017-07-28 10:29:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-28 10:29:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 First action failed
,ok 771 second action killed
,# teardown
,2017-07-28 10:29:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 772 secrets are equal
,ok 773 Public key matches with the server key
ok 774 hostAddress must match
,ok 775 portNumber must match
,ok 776 suggestedTCPTimeout must match
,ok 777 connectionType must match
,# teardown
,2017-07-28 10:29:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 778 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 779 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 780 All entries should be expired after 1 second
# teardown
,2017-07-28 10:29:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 781 All keys need to be available in the cache
,ok 782 All entries should be expired after 1 second
,# teardown
,2017-07-28 10:29:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 783 Size of the cache should be 2
ok 784 Cache doesn't contain dictionary1
,ok 785 Size of the cache should be 1
ok 786 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-28 10:29:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 787 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 788 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-28 10:29:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 789 StartUpdateAdvertisingAndListening should not be called
,ok 790 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 791 no error
,ok 792 should be 204
,# teardown
,2017-07-28 10:29:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-28 10:29:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 794 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-28 10:29:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-28 10:29:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 802 error should be null
,ok 803 should be 204
,# teardown
,2017-07-28 10:29:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 804 should be 404
,# teardown
,2017-07-28 10:29:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 805 equal keys
ok 806 not equal connection type
ok 807 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-28 10:29:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 808 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 809 second cleared dictionary
,2017-07-28 10:29:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-28 10:29:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-28 10:29:44 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-28 10:29:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-28 10:29:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:29:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-28 10:29:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 845 right error
,# teardown
,2017-07-28 10:29:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-28 10:29:47 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-28 10:29:47 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 846 right error
,# teardown
,2017-07-28 10:29:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-28 10:29:48 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-28 10:29:48 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 847 Got error as expected
,# teardown
,2017-07-28 10:29:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 848 Got error as expected
,# teardown
,2017-07-28 10:29:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-28 10:29:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-28 10:29:52 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-28 10:29:53 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-28 10:29:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 850 should be equal
,ok 851 All tests passed!
,# teardown
,2017-07-28 10:29:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-28 10:29:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-28 10:29:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-28 10:30:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-07-28 10:30:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-28 10:30:03 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-28 10:30:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-28 10:30:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 854 action should be killed
ok 855 Error should be timed out
,ok 856 No doc found
,# teardown
,2017-07-28 10:30:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-28 10:30:07 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-28 10:30:07 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 857 should be equal
,2017-07-28 10:30:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-28 10:30:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 858 action should be killed
,ok 859 Error should be timed out
,# teardown
,2017-07-28 10:30:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 860 socket hung up
,# teardown
,2017-07-28 10:30:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 861 same getPeerAdvertisesDataForUs
ok 862 Same pouchdB
ok 863 same localDbName
ok 864 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-28 10:30:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'listening 49170'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] Browser.startListening
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:538E926E-B201-4924-A207-2E81E539D7B5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0)
2017-07-28 10:30:13 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"538E926E-B201-4924-A207-2E81E539D7B5","generation":0}]'
2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"538E926E-B201-4924-A207-2E81E539D7B5","generation":0}'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"538E926E-B201-4924-A207-2E81E539D7B5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:30:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"538E926E-B201-4924-A207-2E81E539D7B5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 538E926E-B201-4924-A207-2E81E539D7B5 (syncValue: 3)'
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0)
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"746F6ED9-D195-4EAC-8676-23249C3D2C78","generation":0}]'
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"746F6ED9-D195-4EAC-8676-23249C3D2C78","generation":0}'
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"746F6ED9-D195-4EAC-8676-23249C3D2C78","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:30:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"746F6ED9-D195-4EAC-8676-23249C3D2C78","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49173
,2017-07-28 10:30:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":49173}'
,2017-07-28 10:30:16 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 746F6ED9-D195-4EAC-8676-23249C3D2C78 (syncValue: 4)'
,2017-07-28 10:30:16 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [1, 11, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Advertiser: session connected Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Advertiser: session connected Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41 state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [1, 11]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 11, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:30:17 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 11, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 11, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [1, 11, 19, 20, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [1, 11, 19, 20, 21, 22, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [1, 11, 19, 20, 21, 23]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [1, 11, 19, 20, 21, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:24 [1, 11, 19, 20, 21, 23]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [1, 11, 19, 20, 21, 23, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [1, 11, 19, 20, 21, 23, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49185
,2017-07-28 10:30:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":49185}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [1, 11, 19, 20, 21, 23, 25, 26, 27]
[ThaliCore] BrowserRelay.didOpenVirtualSocketSt,reamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [1, 11, 19, 20, 21, 23, 25, 26]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [1, 11, 19, 20, 21, 23, 26]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [1, 11, 19, 20, 21, 23, 26, 28]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:30:19 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-28 10:30:19 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [1, 11, 19, 20, 21, 23, 26, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:30:19 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] Session.session(_:peer:didChange:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 31, 32]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 32]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.sock,etDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,5 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-28 10:30:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 37, 38, 39]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 37, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-28 10:30:21 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:38
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:38 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 37, 39, 40]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-28 10:30:21 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 39, 40, 41, 42]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 39, 40, 41, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 39, 40, 41, 42, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:30:21 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
,[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [1, 11, 19, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 39, 40, 41, 43, 44]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-28 10:30:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-28 10:30:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:19
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:19 [1, 11, 20, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 39, 40, 41, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] VirtualSocket.deinit vsID:20 [1, 11, 21, 23, 26, 28, 29, 30, 33, 34, 35, 36, 39, 40, 41, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [1, 11, 23, 26, 28, 29, 30, 33, 34, 35, 36, 39, 40, 41, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [1, 11, 23, 28, 29, 30, 33, 34, 35, 36, 39, 40, 41, 43, 44]
,2017-07-28 10:30:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-28 10:30:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliC,ore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:30
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] Virtua,lSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [1, 11, 23, 29, 30, 33, 34, 35, 36, 39, 40, 41, 43, 44]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [1, 11, 23, 30, 33, 34, 35, 36, 39, 40, 41, 43, 44]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [1, 11, 23, 33, 34, 35, 36, 39, 40, 41, 43, 44]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket.deinit vsID:44 [1, 11, 23, 33, 34, 35, 36, 39, 40, 41, 43]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
2017-07-28 10:30:23 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}]'
,2017-07-28 10:30:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}'
,2017-07-28 10:30:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:30:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:30:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 5)'
,2017-07-28 10:30:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) found active relay
,2017-07-28 10:30:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":65423}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [1, 11, 23, 33, 34, 35, 36, 39, 40, 41, 43, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [1, 11, 23, 33, 34, 35, 36, 39, 40, 41, 43]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDi,sconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:23 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-28 10:30:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 6)'
,2017-07-28 10:30:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) found active relay
,2017-07-28 10:30:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":65423}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [1, 11, 23, 33, 34, 35, 36, 39, 40, 41, 43, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
[ThaliCore] VirtualSocket.deinit vsID:46 [1, 11, 23, 33, 34, 35, 36, 39, 40, 41, 43]
,2017-07-28 10:30:23 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-28 10:30:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 7)'
,2017-07-28 10:30:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) found active relay
,2017-07-28 10:30:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":65423}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [1, 11, 23, 33, 34, 35, 36, 39, 40, 41, 43, 47]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [1, 11, 23, 34, 35, 36, 39, 40, 41, 43, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.sock,etDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.handleEventOnInputStream end,Encountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:35 [1, 11, 23, 34, 36, 39, 40, 41, 43, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDi,dDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:40 [1, 11, 23, 34, 36, 39, 41, 43, 47]
[ThaliCore] VirtualSocket.handleEventOnInputStream endE,ncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:36 [1, 11, 23, 34, 39, 41, 43, 47]
[ThaliCore] TCPClient.socketDidDisconn,ect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:23 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,34
[ThaliCore] VirtualSocket.deinit vsID:34 [1, 11, 23, 39, 41, 43, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore], AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered ,vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconn,ecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [1, 11, 23, 41, 43, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] Adverti,serRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [1, 11, 23, 43, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withEr,ror:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [1, 11, 23, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-28 10:30:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 8)'
2017-07-28 10:30:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) found active relay
,2017-07-28 10:30:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":65423}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [1, 11, 23, 47, 48]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [1, 11, 23, 47]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-28 10:30:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 9)'
2017-07-28 10:30:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) found active relay
2017-07-28 10:30:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":65423}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [1, 11, 23, 47, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [1, 11, 23, 47]
,2017-07-28 10:30:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65423
[ThaliCore] Session.disconnect() peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) relay removed
,2017-07-28 10:30:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}]'
2017-07-28 10:30:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}'
,2017-07-28 10:30:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-28 10:30:26 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28 10:30:26 - WARN thaliNotificationClient: 'peer is not avai,lable'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65427
,[ThaliCore] Session.disconnect() peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
2017-07-28 10:30:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:33:14 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-28 10:33:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4,DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4,DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4,DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4,DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-28 10:40:12 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,nts plugin delay interval'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-28 10:40:12 - INFO Coordi,natedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueu,e and run in order'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-28 10,:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-28 10:40:12 - IN,FO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-28 10:40:13 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-28 10:40:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 865 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-28 10:40:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4,DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4,DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:43:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:43:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:43:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE,9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:43:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/CBDF8B8E-F822-4DE9-9DF3-09937A2349E2/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
